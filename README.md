# KNN-and-Soft-Margin-SVM-using-Pytorch
KNN and Soft-Margin SVM using only Pytorch 
You will find KNN and Soft-margin SVM on MNIST dataset. 
## Problem #1: Load MNIST data 

Data split
Write a function that splits the MNIST dataset into 70% train, 15% val,
15% test sets. Make sure that the number of examples for each class (digit) is distributed
to three sets according to the ratio (i.e., ∼70% of digit 1 in train, ∼15% of digit 1 in val,
∼15% of digit 1 in test, ∼70% of digit 2 in train, ∼15% of digit 2 in val, ∼15% of digit 2
in test, etc.). Afterwards, you will need to convert the fetched data into PyTorch Tensor
type. Normalize the input image data by dividing by 255 to ensure that the input values
are from 0 and 1.

## Problem #2: Binary Classification via k-NN 
a) Make a k-NN (k=5) and its training/validation/evaluation code to perform binary classification between digit 2 and 3.
b) What are the hyperparameters you can tune?
c) Try at least two other options for each hyperparameter. Report the performance for
each option.
d) You can try more options if you want. What is the final test accuracy?


## Problem #3: Multiclass Classification via k-NN 
a) Make a k-NN (k=5) and its training/validation/evaluation code to perform multiclass
classification over all digits.
b) What are the hyperparameters you can tune?
c) Try at least two other options for each hyperparameter. Report the performance for
each option.
d) You can try more options if you want. What is the final test accuracy?


## Problem #4: Binary Classification via soft-margin SVM 
a) Make a SVM classifier and its training/validation/evaluation code to perform binary
classification between digit 2 and 3.
b) Train for 10 epochs with batch size 64 (1 epoch is equal to one entire passing of the
train set; i.e., the entire train set is used for training once).
c) How should we choose the number of iterations to achieve good generalization? Train
until you think the model has achieved good generalization
d) What are the hyperparameters you can tune?
e) Try at least two other options for each hyperparameter. Report the performance for
each option.
f) You can try more options if you want. What is the final test accuracy?

