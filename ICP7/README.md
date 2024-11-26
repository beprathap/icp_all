# ICP-7

Recording link: https://drive.google.com/drive/folders/1RQhJyCOoq7YRVoLlikTu2hMfiuFKENrC?usp=sharing


--> The input shape for the first convolutional layer should be (32, 32, 3) instead of (3, 32, 32). This is because the input_shape parameter expects the dimensions in (height, width, channels) format.
--> The MaxPooling2D layer should have a padding='same' parameter to ensure that the output feature map size is the same as the input feature map size.
--> The Dense layer before the output layer should have a kernel_constraint=maxnorm(3) parameter as well for regularization purposes.
--> Instead of setting the learning rate and decay manually, you can use the learning_rate and decay parameters in the SGD optimizer directly. For example, you can set SGD(lr=0.01, momentum=0.9, decay=1e-6) to achieve the same learning rate and decay as in the original code.
--> As per the ICP, taken 5 epochs and batch size 32.
--> It is evident that the performance has changed.
--> Compared the predicted and actual label for the 4 images and the model has predicted correctly.
--> Finally visualized the model loss and accuracy
