# CaseStudy-CNN
Case Study on Fashion MNIST Dataset

Fashion MNIST is intended as a drop-in replacement for the classic MNIST dataset. This dataset contains images of clothing and apparels which are classified into 10 different types.  Here, 60,000 images are used to train the network and 10,000 images to evaluate how accurately the network learned to classify images. You can access the Fashion MNIST directly from TensorFlow. 

Import and load the Fashion MNIST data directly from TensorFlow as given below:

fashion_mnist = keras.datasets.fashion_mnist
(train_images, train_labels), (test_images, test_labels) = fashion_mnist.load_data()

Tasks:

1.	Write appropriate code to visualize few images from train and test set.
2.	Build a feed-forward neural network model using following information:
o	An input layer with appropriate number of neurons as per the data
o	First hidden layer with 64 neurons and relu activation
o	Second hidden layer with 32 neurons and relu activation
o	An output layer with suitable number of neurons, as per the problem requirements. Use suitable activation function as per the problem requirements.
o	Justify your answer for using a particular activation function, and why not some other activation function.
o	Use appropriate loss function – and state the reason for using the same.
3.	Display the summary of the model built. Give explanation on number of trainable/non-trainable parameters with the mathematical calculation of getting number of trainable/non-trainable parameters. 
4.	Train the model on the training data, by taking validation set as 10% of training set.
5.	Display the training loss and validation loss at every epoch. Display the same as a data frame of history.
6.	Check whether there is an overfitting situation by plotting a suitable graph. If yes, apply appropriate regularization technique to overcome overfitting. Explain the technique used.
7.	Make sure that the validation accuracy is above 90%. 
