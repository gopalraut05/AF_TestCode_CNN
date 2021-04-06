# AF_TestCode_CNN
Proposed Enhance CORDIC Based Activation function validation on CNN

Configurable Activation Function using enhance pipeline stages CORDIC architecture

Three experiment is done for CORDIC based activation function validation using MNIST CIFAR-10 datasets.

Accuracy vs data-bit precision
Accuracy vs # of CORDIC iterations
Accuracy vs dynamic fixed point representation with variable binary point implication
TensorFlow CNN model is used for the test accuracy validation.

Used CNN model: Conv2D -> MaxPooling -> Conv2D -> MaxPooling ->Conv2D -> Flatten -> Dense -> Dense
              (32, 30, 30)           (64, 30, 30)            (64, 30, 30)           (64)      (10)
  
