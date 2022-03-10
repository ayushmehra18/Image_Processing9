# Image_Processing9

# Otsu’s thresholding & K-Means Clustering

1. Calculate the global threshold value of the given images palmleaf1.pgm and palmleaf2.pgm using 
Otsu’s thresholding algorithm, and display the thresholded binary images. Comment on your 
observations.

2. Perform K-means clustering on the two input images (‘car.ppm’ and ‘flower.png’) for K = 3 
clusters. Use only Euclidean distance as the distance measure for all iterations. Basic data units 
to be clustered are vectors containing pixel data, i.e., [r g b]. Perform 5 iterations of the 
algorithm. To visualize the output of k-means clustering, replace each pixel in the input image 
with the cluster centre it belongs to and display the resulting image.
(a) Perform K-means clustering with initial cluster means as follows: 
• c-init 1 - [255 0 0] 
• c-init 2 - [0 0 0] 
• c-init 3 - [255 255 255]

(b) Perform K-means clustering on both images using random initialization of cluster means. Find 
the output corresponding to the lowest and highest value of C.
