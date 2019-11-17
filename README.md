# psychic-pancake

Convolution-It is an operator that helps in extracting features with the help of a kernel or filter that is slinding over input multiplying the corresponding elements and is added which goes into the feature map.

Filters/Kernels-Kernels helps in extracting the features from the input image and reduce the pixel according to the size of the Kernel.

Epochs-To train a machine learning model with huge data set that is training data it not possible due to the limitations of computer memory.It is required to break up data into 
smaller batches which fits computer's memory at once.These batches are fed to the model.Exactly once all the batches are fed which makes one EPOCH.

1x1 Convolution- It is used to reduce the number of depth channels. It simple maps an input pixel of the channels to an output pixel and also summarize the input features maps.

3x3 Convolution-It is the filter of size 3*3 which is slinding over input multiplying the corresponding elements and is added which goes into the feature map.

Feature Maps-The output of the filter or a Kernel is called as feature map.

Activation Function-it is a function that makes output non-linear.The output of the convolution will be passed via the activation function.
Example-ReLU activation function.

Receptive Field-refers to the part of the image that is visible to one filter or a kernel at a time.
Two types:
Local receptive field-The region in the input image that is visible to only that filter or kernel.
Globle receptive field-The regions visible to the final feature map of an input image after a series of convolutions.

score = model.evaluate(X_test, Y_test, verbose=0)
print(score)=[0.03231280661729433, 0.9912]
