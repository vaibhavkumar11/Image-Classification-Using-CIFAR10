# Image-Classification-Using-CIFAR10

## V1 - Using Random Forests
* The first version of image classification on this dataset has been done using Random Forests Classifier.The classifier gave an accuracy of 46.72%(Scope of improvement still there)

## V2 - Using Convolutional Neural Networks
* This version of image classification on CIFAR-10 uses 3-layers of CNN along with 1-Dense layer.
* The code has been written using the Keras deep learning library with a Tensorflow backend.
* An accuracy of 84% is achieved on Train dataset and of 79.9% on the Test dataset.
* A significant gain is seen from the earlier version of image classification which used the Random Forest classifier.

## V2 - Using Convolutional Neural Networks along with data augmentation
* This version uses the Image Generator function inside Keras for data augmentation.
* A lower accuracy is achieved on the train dataset(75%) and a higher accuracy(79%) on test dataset.
* Test dataset is different from the train dataset and this helps in achieving this higher dataset.
* A different model architecture is used to get better results(6 CNN Layers with 1-Dense Layer).
