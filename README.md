# About CIFAR-10 Dataset
I couldn't import the CIFAR-10 dataset due to several connectivity issues. However, after a basic research, I 
realized that this dataset is provided in Tensorflow's Keras.


# General Info
I used the DenseNet algorithm provided by TensorFlow. In this code, I used code pieces from the documentation.

The number of "epochs" define how many times the tests run. Every time we fit this model, the current one's 
accuracy increases. However, since this model's accuracy change rate is logartihmic, the overall accuracy 
tends to decrease. The output is given for 15 "epochs" in the file "accuracy_output.txt". 

Overall, it takes more time to train over and over, but it gives us a more accurate solution.

