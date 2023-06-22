# Simple-Computer-Vision-and-Image-Processing-Codes-in-Python
In this you will find simple and easy Computer Vision and Image Processing  Codes in Python

# Image Filters

## Average image filter:
A simple, yet effective way to smooth images. It works by replacing each pixel value in an image with the average value of its neighbors, including itself. This has the effect of eliminating pixel values which are unrepresentative of their surroundings.

**With filter:**

<p align="center">
  <img width="480" height="360" src="https://github.com/AHMEDSANA/Simple-Computer-Vision-Codes-in-Python/assets/73955220/fde8abaf-05e6-4288-97d3-475e277cb26d">
</p>

**Without filter:**

<p align="center">
  <img width="480" height="360" src="https://github.com/AHMEDSANA/Simple-Computer-Vision-Codes-in-Python/assets/73955220/3cbdf3b8-4597-4db4-be45-d2aa23cad3a1">
</p>

## Canny edge detection: 
A popular algorithm for detecting edges in images. It was developed by John F. Canny in 1986, and it is considered to be one of the most efficient and effective edge detection algorithms available.

<p align="center">
  <img width="480" height="360" src="https://github.com/AHMEDSANA/Simple-Computer-Vision-Codes-in-Python/assets/73955220/22960abb-9137-46e8-b4e1-c8c90d5dd36e">
</p>


## Gaussian filter:
A low-pass filter that is used to smooth images. It works by convolving the image with a Gaussian kernel, which is a bell-shaped function. This has the effect of blurring the image and reducing noise.

<p align="center">
  <img width="480" height="360" src="https://github.com/AHMEDSANA/Simple-Computer-Vision-Codes-in-Python/assets/73955220/1a4d61e6-945d-48d5-917e-f8cf3268b400">
</p>

## Median filter:
A non-linear filter that is used to remove salt and pepper noise from images. It works by replacing each pixel value in an image with the median value of its neighbors. This has the effect of preserving edges while removing noise.

<p align="center">
  <img width="480" height="360" src="https://github.com/AHMEDSANA/Simple-Computer-Vision-Codes-in-Python/assets/73955220/c4e3caf5-c501-42e9-928c-2f60a8f033bf">
</p>


## Salt and pepper noise:
A type of noise that is characterized by randomly distributed black and white pixels. It can be caused by sensor noise or by transmission errors.

<p align="center">
  <img width="480" height="360" src="https://github.com/AHMEDSANA/Simple-Computer-Vision-Codes-in-Python/assets/73955220/b9280f51-a75a-4355-a64b-0df56c202f28">
</p>


## Sobel filter:
 A linear filter that is used to calculate the gradient of an image. The gradient is a measure of the rate of change of an image, and it can be used to detect edges.

## Prewitt filter:
A linear filter that is like the Sobel filter, but it uses different coefficients.

<p align="center">
  <img width="480" height="360" src="https://github.com/AHMEDSANA/Simple-Computer-Vision-Codes-in-Python/assets/73955220/0deee85c-f5dd-408b-a73b-a117a674de4c">
</p>


Here is a table summarizing the key properties of these image processing techniques:

| Technique | Purpose | Advantages | Disadvantages |
| --- | --- | --- | --- |
| Average image filter | Smooth images | Simple and easy to implement | Can blur edges |
| Canny edge detection | Detect edges in images | Efficient and effective | Sensitive to parameter choice |
| Gaussian filter | Smooth images | Reduces noise | Can blur edges |
| Median filter | Remove salt and pepper noise | Preserves edges | Can blur edges |
| Salt and pepper noise | Randomly distributed black and white pixels | Can be caused by sensor noise or transmission errors | Can be difficult to remove |
| Sobel filter | Calculate gradient of an image | Simple and easy to implement | Can be sensitive to noise |
| Prewitt filter | Similar to Sobel filter | Simple and easy to implement | Can be sensitive to noise |
