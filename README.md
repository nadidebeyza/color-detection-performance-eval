### Performance Evaluation of the Two Color Detection Algorithms

**Introduction**

In this project perform a performance evaluation of the two image color detection models. These machine learning models automatically turn grayscale images into colored images. 

The first model is called Image Colorization Basic Implementation with CNN and was built by Victor Basu(https://www.kaggle.com/code/basu369victor/image-colorization-basic-implementation-with-cnn/notebook).

The second model is called Colorizing B&W Photos with Neural Networks and was built by Emill Warner(https://blog.floydhub.com/colorizing-b-w-photos-with-neural-networks/).

**Color Detetction Algorithm - 1: Image Colorization Basic Implementation with CNN by Victor Basu**

In the GAN network, the auto-encoder network that is described in this model also serves as a generator.
The goal of this model is to see how well the most basic auto-encoder performs against image colorization. This auto-encoder model is used in conjunction with higher-level or more advanced approaches to get outstanding picture colorization outcomes.
The image was colorized using Lab value, where L refers to brightness and a and b stand for the color spectra green–red and blue-yellow, respectively. It converts the RGB picture to a LAB image, then extracts the L and ab values from the image before training the model to predict the ab value.
Since the model dataset contains only colored images while the model is trained on black and white images, it converts the colored image to grayscale and then to RGB format to achieve complete black and white image conversion. Opencv was also used to read the image, however, because Opencv reads the image in BGR format, it must first convert the image to RGB before converting it to grayscale.

**Color Detetction Algorithm - 2: Colorizing B&W Photos with Neural Networks by Emill Warner**

The model was constructed in three stages.
The first portion deconstructs the central reasoning. As an "Alpha" colorization bot, it creates a simple 40-line neural network.
The next phase is to build a generalizable neural network (the "Beta" version). The model is able to color photos that have never been viewed before by the bot.
It integrates the neural network with a classifier in the "final" form. It employs a Resnet V2 from Inception that has been trained on 1.2 million photos.

**Model-1 Output**

![Example output of the code](https://github.com/nadidebeyza/color-detection-performance-eval/blob/main/Output/model_1/Test-0.png "Example output of the code")

**Model-2 Output**

![Example output of the code](https://github.com/nadidebeyza/color-detection-performance-eval/blob/main/Output/model_2/img_0.png "Example output of the code")

