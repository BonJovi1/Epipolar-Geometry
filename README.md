# Epipolar-Geometry

If the notebook doesn't load on GitHub, use the notebook viewer: \
https://nbviewer.jupyter.org/github/BonJovi1/Epipolar-Geometry/blob/master/code.ipynb

## Instructions

To install Jupyter Notebook, if you don't have it, run
`pip install jupyter` \
And then, run the command `jupyter-notebook code.ipynb`

## The Question

You’ve been given two images of the same scene, taken from different view-points. The fundamental matrix (F) that encodes their relative geometry and a subset of the corresponding points in both the images that were used to estimate F are provided as well.
Given a point in one image, its corresponding location in the other image can be found to be along a line viz. the epipolar line. 

a) For the points in the first image, **plot their corresponding epipolar lines** in the second image as shown. Repeat this for the first image. The convention for F we follow is x′T F x = 0, where x′ is the location of the point in the second (right) image.

b) Epipolar lines must all converge to their respective epipoles. But the epipoles here seem to lie outside the image. (b) How can you compute the locations of these epipoles without using these lines? Report the locations.
