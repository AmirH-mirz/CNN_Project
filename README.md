# CNN_Project
This is for practice
First, we will upload our dataset, as we can see, we have five rice models, that is, we have five classes, we have to divide each of the classes for train, test and validation.
We allocate 75% of each class to train, 20% to test, and 5% to validation.
Then we will create data frames for train, test and validation.
Now we see the length and width of the photos so that there are no different lengths and widths among the photos.
First, we start with a simple model which, as we can see, is very accurate. To solve this problem, we use the Droup_out layer.
In the next model, we use L2 regularization to prevent the weights from getting too large, it prevents overfit.
In the continuation of our model, the accuracy is low, now we use lr_scheduler to increase the accuracy, which reduces the learning rate.
Now the accuracy of our model has decreased a lot, now we increase the accuracy of our model by adding BatchNormalization and convolution layers.
