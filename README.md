Assignment 3 - Community Detection

Here's the data set for the assignment.

Dolphins(https://ece.iisc.ac.in/~rajeshs/E0259/dolphins.zip) with due thanks to Lusseau et al. (2003) for compiling the data, and to Mark Newman for creating the file. Unzip the .zip file to see two files, dolphins.txt (description) and dolphins.gml which contains an undirected social network of frequent associations between 62 dolphins in a community off Doubtful Sound, New Zealand. You can use the NetworkX package in Python to read the file or any other similar tool.

Two circles(https://ece.iisc.ac.in/~rajeshs/E0259/11_twoCirclesData.csv) with due thanks to Nihesh Rathod for generating the data. The .csv file contains the x and y coordinates of several points.

Tasks completed -

1. Identify the two communities in the dolphins data set by obtaining the Fiedler vector of the normalised Laplacian. Provide a visualisation of the outcome so that the names of the dolphins, the network, and the two communities are clearly visible. Indicate the approach you have taken in light of the fact that the two communities are of different sizes.

2. Follow the method outlined in slide 31 to generate the "adjacency" matrix. Choose the top two eigenvectors and use the k-means algorithm on the rows to arrive at your two clusters. Provide a picture of your outcome to demonstrate that the circles have been captured. Choose the parameter with some care in order to capture the two circles.

You can use existing Python packages (for eigenvectors, eigenvalues, but the spectral clustering algorithm implementation and k-means algorithm implementation should be your own).
