# Datasheet Template

As far as you can, complete the model datasheet. If you have got the data from the internet, you may not have all the information you need, but make sure you include all the information you do have. 

## Motivation

The MNIST database was created to provide a testbed for people wanting to try pattern recognition methods or machine learning algorithms while spending minimal efforts on preprocessing and formatting. 


## Composition

Images of the original dataset (NIST) were in two groups, one consisting of images drawn by Census Bureau employees and one consisting of images drawn by high school students. In NIST, the training set was built by grouping all the images of the Census Bureau employees, and the test set was built by grouping the images form the high school students. 

## Collection process

The goal in building MNIST was to have a training and test set following the same distributions, so the training set contains 30,000 images drawn by Census Bureau employees and 30,000 images drawn by high school students, and the test set contains 5,000 images of each group. The curators took care to make sure all the images in the test set were drawn by different individuals than the images in the training set.

## Preprocessing/cleaning/labelling

The original images from NIST were size normalized to fit a 20x20 pixel box while preserving their aspect ratio. The resulting images contain grey levels (i.e., pixels don't simply have a value of black and white, but a level of grayness from 0 to 255) as a result of the anti-aliasing technique used by the normalization algorithm. The images were then centered in a 28x28 image by computing the center of mass of the pixels, and translating the image so as to position this point at the center of the 28x28 field.

## Uses

The dataset is for use in developing machine learning image classification algorithms.

## Distribution

The dataset is widely distributed on Machine Learning websites.

## Maintenance

n/a

