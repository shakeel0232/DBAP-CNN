#  DBAP-CNN

Classification accuracy yielded by LeNet and AlexNet (in %) after incorporation of DBAP layer.The classifier used is softmax,SVM and Knn by both the models(LeNet and AlexNet). One can observe that the results are better than those achieved by the baseline models and competitive to the discrimination results of other popular deepmodels.

if you want to use other datasets change the import file form mnist to cifar10 and fashion-mnist from (import keras.datasets import.cifar10 ) and load (x_train, y_train), (x_test, y_test) = cifar10.load_data() and (x_train, y_train), (x_test, y_test) = fashion_mnist.load_data() 

To run code go to Google Colab (https://colab.research.google.com/notebooks/intro.ipynb#recent=true)

or 

Set up your environment.
Install Keras.
Import libraries and modules.
Load image data from MNIST.
Preprocess input data for Keras.
Preprocess class labels for Keras.
Define model architecture.
Compile model.



