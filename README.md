[//]: # (Image References)

[image1]: ./images/out.png "Sample Output"
[image2]: ./images/vgg16_model.png "VGG-16 Model Layers"
[image3]: ./images/vgg16_model_draw.png "VGG16 Model Figure"


## Project Overview

This project shows how to build a pipeline that can be used within a web or mobile app to process real-world, user-supplied images.  Given an image of a dog, the algorithm identifies an estimate of the canine’s breed.  If supplied an image of a human, the resembling dog breed is shown.  

![Sample Output][image1]

## References

### Datasets
1. [dog dataset](https://s3-us-west-1.amazonaws.com/udacity-aind/dog-project/dogImages.zip).  The `dogImages/` folder contains 133 folders, each corresponding to a different dog breed.
2. [human dataset](http://vis-www.cs.umass.edu/lfw/lfw.tgz) for testing on human images. 

### Libraries
Pytorch, OpenCV, numpy, matplotlib, glob, tqdm, PIL, torchvision, os

### Software
Jupyter notebook, Python 3


