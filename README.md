# Face Mesh with Mediapipe and OpenCV

This project demonstrates real-time **3D face landmark detection** using **MediaPipe FaceMesh** and **OpenCV**.
The program draws the full face mesh, highlights the **nose tip**, **eyes**, and **mouth**, and displays the **FPS counter**.

---

## Features

* Capture live video from a webcam.
* Render the **468-point face mesh**.
* Highlight the **nose tip** with a red circle.
* Highlight **eyes** in blue.
* Highlight **mouth** in orange.
* Show the **FPS** in the top-left corner.
* Mirror the video feed (natural mirror effect).
* Close the program with the `Esc` key.

---

## Installation

1. Clone this repository or save the script locally.
2. Install the required packages:

```bash
pip install -r requirements.txt
```

## Run

Launch the script with:

```bash
python SMP.py
```

Once started, the webcam window will open showing:

* The face mesh overlay
* The red nose tip marker
* Eyes in blue
* Mouth in orange
* The FPS counter

Press `Esc` to exit.

---

## Useful Links

* [MediaPipe FaceMesh Documentation](https://developers.google.com/mediapipe/solutions/vision/face_mesh)
* [OpenCV Documentation](https://docs.opencv.org/)
