# Image Processing with PIL and OpenCV (cv2)

This repository demonstrates basic image processing using **PIL (Pillow)** and **OpenCV (cv2)** in Python. Both libraries are widely used for reading, displaying, and manipulating images.

---

## PIL (Python Imaging Library / Pillow)

PIL (now maintained as **Pillow**) is a Python library that provides simple tools for image processing. It is commonly used for basic image operations and works well with Python data workflows.

### Reading an Image

```python
from PIL import Image

img = Image.open("image.jpg")
img.show()

```

OpenCV (cv2) is a powerful computer vision library designed for high-performance image and video processing. It is commonly used in real-time applications.
```python
import cv2

img = cv2.imread("image.jpg")
```
