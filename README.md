# star-type-classification

Building models of ML for classification of star type.

Features:

Temperature
L - Luminousity
R - Radius
AM - Absolute Magnitude.
Color -- General Color of Spectrum
Spectral_Class 

TARGET:
Type -- Red Dwarf, Brown Dwarf, White Dwarf, Main Sequence , Super Giants, Hyper Giants

Star types are label as --

Red Dwarf - 0
Brown Dwarf - 1
White Dwarf - 2
Main Sequence - 3
Super Giants - 4
Hyper Giants - 5

Algorithms used for training the model are Random Forest Classifier and K-Nearest Neighbors Classifier.

Accuracy score --
Random Forest Classifier : 100%
Final Result for Random Forest :

![rf](https://user-images.githubusercontent.com/87939645/127537802-20d3987a-164e-4197-8fe7-366afe0c1bd1.JPG)


K-Nearest Neighbors Classifier : 97.9%
Final result for KNN :

![knn](https://user-images.githubusercontent.com/87939645/127537758-ca96206e-826f-405a-9f7e-b3865529dc8f.JPG)

Training vs test accuracy score graph for KNN model:

![knn2](https://user-images.githubusercontent.com/87939645/127538449-7ce7bcdf-b565-4761-8df4-a69775c3093d.JPG)
