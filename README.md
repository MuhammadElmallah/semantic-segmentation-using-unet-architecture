# semantic-segmentation-using-unet-architecture

Kaggle Link: https://www.kaggle.com/muhammadelmallahka/good-start-for-beginners

In this notebook, I am trying to approach the task of semantic segmentation, classifying each pixel in an image from a set of classes that are previously defined.

The main goal in this task is to take an image of size (Width x Height x 3) and generate a (Width x Height) matrix containing the predicted class corresponding to each pixel in the image.

I have used the Unet architecture and I have reached accuracy of about 86 %.

I have used the Earystopping callback to avoid overfitting.

As future work, I will use transfer learning and Data Augmentaion to improve the accuracy without overfitting the data.

