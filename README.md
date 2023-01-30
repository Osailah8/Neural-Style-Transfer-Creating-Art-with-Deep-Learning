# Neural Style Transfer Creating Art with Deep Learning

## Introduction
Neural style transfer is a deep learning technique that combines the content of one image with the style of another to create a new, stylized image. The process involves training a convolutional neural network (CNN) on a dataset of images, with the goal of learning to generate new images that preserve the content of the input image while adopting the style of the reference image.
<img src="https://i.imgur.com/0tS0t5c.png" width="400px">

To achieve this, the model is trained using two loss functions: a content loss function that measures the difference between the content of the input image and the stylized output image, and a style loss function that measures the difference between the style of the reference image and the stylized output image. By minimizing these loss functions, the model is able to generate an output image that has the same content as the input image, but with the style of the reference image.

![Alt text](https://i.imgur.com/pg6J5xC.png)

Neural style transfer has many potential applications in fields such as computer graphics, image processing, and advertising. The code provided for implementing neural style transfer includes a pipeline using the VGG19 CNN model and allows for customization and experimentation with various parameters such as the model and optimizer to use, the loss weights, and the number of optimization steps.

Overall, neural style transfer is a powerful tool for creating artistic images and improving the quality of images, and has the potential to have a significant impact in a variety of fields.


## Content Images Dataset (with images name)
https://www.wikiart.org/ 

## Content Images Dataset (by number)
https://www.kaggle.com/datasets/flash10042/abstract-paintings-dataset

## Style Image 
<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/e/ea/Van_Gogh_-_Starry_Night_-_Google_Art_Project.jpg/400px-Van_Gogh_-_Starry_Night_-_Google_Art_Project.jpg">


