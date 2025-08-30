# Face Mesh with Mediapipe and OpenCV

This project demonstrates the use of **MediaPipe FaceMesh** for capturing and visualizing 3D face landmarks in real-time with **OpenCV**.  
The program renders the face mesh and highlights the nose tip.

---

## Features
- Capture video from a webcam.
- Draw a face mesh (**468 landmarks**).
- Highlight the nose tip with a red circle.
- Mirror the image (like a real mirror).
- Exit with the `Esc` key.

---

## Installation

1. Clone the repository or save the code locally.
2. Install the dependencies:

```bash
pip install -r requirements.txt
````

The `requirements.txt` contains:

```
opencv-python
mediapipe
numpy
```

---

## Run

Run the script with:

```bash
python SMP.py
```

After launching, a window with the webcam feed will appear showing the drawn face landmarks.
Press `Esc` to close the program.

---

## Requirements

* Python 3.8+
* Webcam
* OpenCV and MediaPipe support

---

## Useful Links

* [MediaPipe FaceMesh Documentation](https://developers.google.com/mediapipe/solutions/vision/face_mesh)
* [OpenCV Documentation](https://docs.opencv.org/)

---
