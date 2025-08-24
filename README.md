# Face Detection with MTCNN and OpenCV

This project demonstrates face detection and facial keypoint localization using the [MTCNN](https://pypi.org/project/mtcnn/) (Multi-task Cascaded Convolutional Networks) library together with [OpenCV](https://opencv.org/).

The script loads an image, detects faces, marks key facial points (eyes, nose, mouth), and draws bounding boxes around detected faces.

---

## Features
- Detects multiple faces in a single image.
- Identifies key facial points:
  - Left eye
  - Right eye
  - Nose
  - Mouth (left and right corners)
- Draws bounding boxes and markers directly on the image.

---

## Requirements

Make sure you have Python 3.7+ installed, then install the dependencies:

```bash
pip install mtcnn opencv-python
