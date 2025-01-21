# Dog-breed-identification
this is an end-to-end multi-class dog-breed image classifier using TensorFlow 2.0 and TensorFlow Hub.

1. Problem
Identifying the breed of a dog given an image of a dog.

2. Data
The data we're using is from Kaggle's dog breed identification competition.
https://www.kaggle.com/competitions/dog-breed-identification/data

3.Preprocessing Images(turning images into Tensors)
To preprocess our images into Tensors we're going to write a function which does a few things:
a.Take an image filepath as input

b.Use TensorFlow to read the file and save it to a variable, image

c.Turn our image (a jpg) into Tensors

d.Resize the image to be a shape of (224,224)

e.Return the modified image

4. Evaluation
The evaluation is a file with prediction probabilities for each dog breed of each test image.
https://www.kaggle.com/competitions/dog-breed-identification/overview/evaluation

5. Features
Some information about the data:

a.We're dealing with images(unstructured data) so it's probably best we use deep learning/transfer learning.
b.There are 120 breeds of dogs (this means there are 120 different classes.)
c.There are around 10,000+ images in the training set(these images have labels).
d.There are around 10,000+ images in the test set (these images have no labels, because we'll want to predict them).
