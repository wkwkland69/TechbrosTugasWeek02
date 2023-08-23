
iris_120_set - v7 2022-09-01 10:16am
==============================

This dataset was exported via roboflow.com on September 1, 2022 at 1:17 AM GMT

Roboflow is an end-to-end computer vision platform that helps you
* collaborate with your team on computer vision projects
* collect & organize images
* understand unstructured image data
* annotate, and create datasets
* export, train, and deploy computer vision models
* use active learning to improve your dataset over time

It includes 5783 images.
Ring are annotated in YOLO v5 PyTorch format.

The following pre-processing was applied to each image:
* Auto-orientation of pixel data (with EXIF-orientation stripping)

The following augmentation was applied to create 3 versions of each source image:
* 50% probability of horizontal flip
* 50% probability of vertical flip
* Randomly crop between 0 and 30 percent of the image
* Random Gaussian blur of between 0 and 3.5 pixels
* Salt and pepper noise was applied to 5 percent of pixels


