This is a final project for the machine learning course part II (Intelligent Datenanalysis & Machine Learning II) at the university of Potsdam (Master of Science). 
It is a multiclass image classification task on CIFAR-10 dataset. 
Different architectures (combinations of FCNN with CNN) were tried out. Such technic as dropout was used to prevent overfitting. Some experiments with dimensionality reduction by using of principal component analyses were caried out. The power of the best architecture was also tested on the same data, that was gray-scaled. 
The accuracy of 77,5% (the effect of overfitting was controlled and was reduced quite successfully by a well-tuned dropout regularisation method) was achieved with the following architecture:
3 convolutional layers (kernel size = 3x3, stride = 1, padding = 1, activation function Leaky ReLU, max pooling layer after each conv. layer with 4x4 kernel and stride=2)    
2 fully-connected layer (256 neurons each)

The final grade for this project was 2,0. 
