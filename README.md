# ML-CIFAR10
Basic ANN and CNN models of CIFAR-10 dataset

In this mini project, I trained and tested the CIFAR-10 dataset using 
(1) Artificial neural network(ANN) model
(2) Convolutionary neural network(CNN) model.

The CIFAR-10 dataset contains 60,000 32x32 images in 10 different classes.The 10 different classes represent airplanes, cars, birds, cats, deer, dogs, frogs, horses, ships, and trucks. There are 6,000 images of each class.

I used 'relu' activation function in my model for input data and 'softmax' activation function for output. (As output gives probability to be between 0 and 1).

From these models,
I concluded that on increasing the no. of epochs,the accuracy of model first increases upto a certain no. of epochs and then the accuracy decreases due to over-fitting of data.

Further, accuracy also depends on no. of hidden layers used. I used two hidden layers as increasing it to 3 was giving lesser accuracy..

Further, CNN model takes much larger time than ANN model because it uses convolution and pooling layers but it gives better accuracy than ANN model.

Thus, CNN gives better accuracy than ANN but takes longer time...
