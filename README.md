# 🧠 Object Detection using OpenCV

**Author:** Ritesh Hon
**Description:** This project demonstrates real-time object detection using OpenCV’s DNN module and the pre-trained MobileNet-SSD model. It uses OpenCV’s deep learning capabilities to detect multiple objects from a webcam feed with bounding boxes and class labels.

---

## ✨ Key Features

* Real-time object detection using a webcam feed.
* Uses MobileNet-SSD (Single Shot Detector) trained on COCO dataset.
* Displays bounding boxes and object labels with confidence scores.
* Applies **Non-Maximum Suppression (NMS)** to remove overlapping boxes.

---

## 📷 Example Output

![Test](https://github.com/riteshhon7709/Object-Detection-with-OpenCV-/blob/master/Images/SampleDetection.png)

---

## 🎓 Credits

Special thanks to **Murtaza Hassan** for his tutorials:

* [YouTube Tutorial](https://www.youtube.com/watch?v=HXDD7-EnGBY)
* [Project Page](https://www.murtazahassan.com/courses/opencv-projects/lesson/code-and-files/)

---

## 🛠️ Prerequisites

* Anaconda (or Python 3.8+ with `opencv-python`)
* Git

---

## 🚀 Getting Started

### 📦 Step 1: Clone the Repository

```bash
git clone https://github.com/riteshhon7709/Object-Detection-with-OpenCV-.git
```

### 📁 Required Files

The following files are necessary to run the model:

* **coco.names** – List of detectable objects (e.g., person, car, dog, etc.)
* **frozen\_inference\_graph.pb** – Pre-trained weights for MobileNet-SSD.
* **ssd\_mobilenet\_v3\_large\_coco\_2020\_01\_14.pbtxt** – Configuration for the detection model.

> ✅ These files are already included in the repository (or available from TensorFlow’s model zoo if missing).

---

### 🐍 Step 2: Set Up the Conda Environment

Open the Anaconda terminal and navigate to the project folder. Run:

```bash
conda env create -f objectdetectioncv.yml
```

Then activate the environment:

```bash
conda activate objectdetectioncv
```

---

### ▶️ Step 3: Run the Program

Navigate to the source directory and run the detection script:

```bash
cd Object-Detection-with-OpenCV-/source
python main_webcam.py
```

---

## 🧠 How It Works

1. The MobileNet SSD model detects objects from the webcam stream.
2. The detection outputs include class IDs and confidence scores.
3. OpenCV draws bounding boxes for detected objects with confidence above a threshold.
4. **Non-Maximum Suppression (NMS)** ensures no duplicate boxes are shown for the same object.

---

## 📩 Contact

For questions, suggestions, or collaboration:
📧 [riteshhon7709@gmail.com](mailto:riteshhon7709@gmail.com)
🔗 [LinkedIn](https://www.linkedin.com/in/ritesh-hon/)

