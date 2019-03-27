# Intel-image-classification-Kaggle
The image data of Natural Scenes around the world.Want to build powerful Neural network that can classify these images with more accuracy.

Link to the original problem statement on kaggle : https://www.kaggle.com/puneet6060/intel-image-classification


Files/directories used in the code:

categories :- jason file containig the 6 different classes ('buildings','forest','glacier','mountain','sea', 'street').

seg_train and seg_pred which are contained in a folder called classification which holds training and validation images.

seg_pred :- containing the images to be predicted.


I ran the Resnet 152 model and updated the pre-trained weights by training it on the train images dataset.
Acheived an overall accuracy of 90.7% on the validation dataset (seg_test).


I have uploaded both an offline notebook as well as my google-colab notebook.



