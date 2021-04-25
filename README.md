# Fruit Localization and Detection
Both models (Simple and Advance) are implemented in Tensorflow



## Simple Model

In this model, I have first created images and their respective labels (i.e. object type, object's location).

Then, A custom model has been created with output layer consisting of 4 neurons for object's location, 1 for object's apperance in the image and 2 for object types

Also, a custom loss function is implemented in such a way that it consider object's location and object types only if the object is present in the image.

At last, I have implemented custom callback, which saves the model when the loss is minimum and the training stops if the loss doesn't reduce for 6 epochs in straight.

## Advance Model

*It's under construction.
