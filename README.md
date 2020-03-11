# Blur It
This package is aimed to build to blur different portions of a image. Currently it blurs eyes in human photograph.

[![PyPI version](https://badge.fury.io/py/blurit.svg)](https://badge.fury.io/py/blurit)

## Install
```sh
pip install blurit
```

## Usage
```sh
from blurit import blur_eyes_in_images

#blur_eyes_in_images('[YOUR-IMAGES-FOLDER-PATH]','[GENERATED-IMAGES-FOLDER PATH]','VALUE-OF-HEIGHT-AND-WIDTH-OF-BLUR')
blur_eyes_in_images('./images','./images_generated',15)

```



## Demo
- I have used a selfie of elen from [here](https://www.gannett-cdn.com/-mm-/43a1a3523af941a87e3b16e3c278f5b2a05102a0/c=2-0-1022-576/local/-/media/2017/06/21/USATODAY/USATODAY/636336409269948637-AP-YE-86TH-ACADEMY-AWARDS-69181576.JPG?width=660&height=373&fit=crop&format=pjpg&auto=webp) and compiled the code. looks as below.

<img src="https://github.com/bharatpabba/blur-it/blob/master/images_generated/1.jpeg" />

## I have used the help from below posts to build this package

1. [How to draw a rectangle around a region of interest in python](https://stackoverflow.com/questions/23720875/how-to-draw-a-rectangle-around-a-region-of-interest-in-python)
2. [How to use opencv (python) to blur faces?](https://stackoverflow.com/questions/18064914/how-to-use-opencv-python-to-blur-faces)
3. [Gaussian blurring with OpenCV: only blurring a subregion of an image?](https://stackoverflow.com/questions/24195138/gaussian-blurring-with-opencv-only-blurring-a-subregion-of-an-image)
