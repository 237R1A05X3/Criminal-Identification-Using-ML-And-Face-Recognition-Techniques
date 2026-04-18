# 🔍 Criminal Identification using Face Recognition

## 📌 Project Overview

This project is a Machine Learning-based Criminal Identification System that detects and recognizes human faces from images. It uses advanced deep learning models like MTCNN for face detection and FaceNet for feature extraction, along with an SVM classifier for accurate identification.

The system provides a simple GUI where users can upload datasets, train the model, and identify a person with confidence percentage.

---

## ⚙️ Technologies Used

* Python
* OpenCV
* MTCNN (Face Detection)
* FaceNet (Feature Extraction)
* Support Vector Machine (SVM)
* Tkinter (GUI)
* NumPy, Matplotlib, Seaborn

---

## 💻 Prerequisites (System Requirements)

Before running this project, ensure your system has:

* Python 3.7 or above installed
* pip (Python package manager)
* Internet connection (for first-time model loading)

---

## 📦 Required Libraries

Install all dependencies using:

```bash
pip install -r requirements.txt
```

Or install manually:

```bash
pip install opencv-python numpy mtcnn keras-facenet scikit-learn matplotlib seaborn pillow
```

---

## 📁 Project Structure
CriminalIdentification/
│── CriminalIdentification.py
│── dataset/
│── requirements.txt
│── README.md
---

## 🧠 Working Process

1. Upload dataset containing images of different persons
2. Detect faces using MTCNN
3. Extract facial features using FaceNet
4. Normalize feature vectors
5. Train SVM classifier
6. Predict identity from new image
7. Display result with confidence percentage

---

## 🚀 Features

* Face detection using MTCNN
* Face recognition using FaceNet + SVM
* Confidence score display
* Graph visualization (Accuracy, Precision, Recall, F1 Score)
* Confusion matrix visualization
* Simple GUI using Tkinter

---

## 📊 Performance Metrics

The model evaluates performance using:

* Accuracy
* Precision
* Recall
* F1 Score

---

## ▶️ How to Run the Project

### Step 1: Clone Repository

```bash
git clone https://github.com/your-username/criminal-identification-face-recognition.git
cd criminal-identification-face-recognition
```

### Step 2: Install Dependencies

```bash
pip install -r requirements.txt
```

### Step 3: Run Application

```bash
python CriminalIdentification.py
```

---

## 📸 Output

* Detects face in the image
* Draws bounding box around face
* Displays predicted name
* Shows confidence percentage

---

## 🎯 Future Improvements

* Real-time face recognition using webcam
* Improve accuracy with larger dataset
* Add unknown person detection
* Deploy as web application

---

## 👨‍💻 Author

* Palle Amulya
* Durshetti Charan Teja
* Odela Sai Charan
* Md. Madiya
---

## 📌 Note

This project is developed for educational and academic purposes.
