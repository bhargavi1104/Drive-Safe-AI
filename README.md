# 🚗 Driver Drowsiness Detection

The **Driver Drowsiness Detection System** uses **dlib** for facial landmark detection and eye tracking to calculate the **Eye Aspect Ratio (EAR)**, which monitors driver fatigue.

**imutils** simplifies video frame processing, while **scipy** helps compute the Euclidean distance between eye landmarks to assess drowsiness.

The system alerts the driver when signs of fatigue are detected, improving road safety by preventing accidents caused by drowsy driving.

---

## 📌 Prerequisites

### 1. Python Version

- Ensure that you are using **Python 3.x** for compatibility.


### 2. Facial Landmarks File

- You need a facial landmarks file, which can be downloaded from the link provided below.

- Extract the file to your working directory for easy access.


### 3. Required Libraries

The following libraries are required for the project:

- **dlib** - Facial landmark detection

- **imutils** - Video frame manipulation

- **scipy** - Mathematical calculations like Euclidean distance

- **opencv-python** - Image and video processing


> Ensure these dependencies are installed using the `requirements.txt` file.

---

## 📂 Dataset / Model File Download

Download the facial landmark predictor file:

🔗 **shape_predictor_68_face_landmarks.dat**

https://sourceforge.net/projects/dclib/files/dlib/v18.10/shape_predictor_68_face_landmarks.dat.bz2/download


---

## ▶️ Execution

Follow these steps to run the system:

### Install Required Libraries

Run the command:

```bash
python -m pip install -r requirements.txt
```


### Run the Main Python File

Execute:

```bash
python Driver_Drowsiness_Detection.py
```


The system will begin capturing video from your webcam, detect facial landmarks, and alert you if signs of drowsiness are detected.

---

## ⚠️ Troubleshooting

### Webcam Issues

- If you encounter issues with video capture, ensure that your webcam drivers are properly installed.

- Make sure your webcam is recognized by OpenCV.


### dlib Installation Issues

- If dlib installation fails, make sure you have the necessary C++ build tools installed.

- Check proper dlib installation requirements before running the project.


---

## 📝 Notes

- The **shape_predictor_68_face_landmarks.dat** file is crucial for accurate facial landmark detection.

- Ensure that the file is extracted and available in the working directory.

- You can also specify its path manually inside the script if required.
