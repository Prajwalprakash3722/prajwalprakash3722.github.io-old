---
title: Introduction to Open-Cv
categories:
  - coding/Image-Processing
excerpt: |
  A brief introduction to a popular module called Open-Cv
feature_text: |
   
feature_image: "https://miro.medium.com/max/3200/1*Cvwue5II1QjdXIhSPGkVUw.png"
image: "https://miro.medium.com/max/3200/1*Cvwue5II1QjdXIhSPGkVUw.png"
---

Hey there, Happy Pride month, This is my first post about a topic related to coding.

You must have heard about Image Processing. Well, what is it?

Image-Processing is processing each pixel of data present in the image, Now don’t tell me you haven’t learned the term PIXEl, if you haven’t here it is, then pixel represents the smallest possible element in an image. Several pixels contribute to a complete image.

open-cv (Open Source Computer Library) an open source pre-trained module which was started in 1999 and written in c++, but the recent algorithms are being written in Python and Java.

Now we are going to learn about the most basic operation in open-cv, which is reading the image.

### Steps:

open a new folder in terminal and initialize virtual environment:

```virtualenv env```

then activate the virtual environment by:

```source env/bin/activate```

install numpy and matplotlib

```pip install numpy```

```pip install matplotlib```

Install OpenCV via pip

```pip install opencv-python```

or install by conda env

```conda install opencv-python```

or if you are a Linux user like me,

```sudo apt install opencv-python```

* Reading an image is basically feeding the image data to the computer, after installing all of the above modules then save a random image in your file.

Then copy the image file path

#### Code Snippet

```python

import cv2 # we are importing the cv2 module from opencv


image_path = “/home/prajwal/OpenCv/image_1.jpeg” #change this path by your image path

image = cv2.imread(image_path) # Reading of image

cv2.imshow(“Image-Reading”, image) # Image output in new Window

cv2.waitKey(0)

cv2.destroyAllWindows()
```
A window with the image and Title "Image-Reading" will pop out
How easy was that, You can do so much more with the opencv? Follow this space regularly to know them.
 
Learn more about [Open-Cv](https://opencv.org/)
##### Thank you.
