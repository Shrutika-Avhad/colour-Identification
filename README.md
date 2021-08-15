# Color-Identification-using-Machine-Learning
This project uses Machine Learning to extract a set number of colors from an image.

Extraction of colors from images using KMeans algorithm and filtering images from a collection of images based on RGB values of colors. The sample_image.jpg was clicked by me and the other 5 images in the folder images were taken from Unsplash.

Import libraries
We import the basic libraries including matplotlib.pyplot and numpy. To extract the count, we will use Counter from the collections library. To use OpenCV, we will use cv2. KMeans algorithm is part of the sklearn's cluster subpackage. To compare colors we first convert them to lab using rgb2lab and then calculate similarity using deltaE_cie76. Finally, to combine paths while reading files from a directory, we import os.
