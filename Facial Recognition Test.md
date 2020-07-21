This challeng is to test candiates capability to categorize facial images into different races and gender. 

The Dataset has 15805 images which are catcategorized into 10 folders: asianman, asianwoman, blackman, blackwoman, indianman, indianwoman, latinoman, latinowoman, whiteman and whitewoman. 

Please built classification models based on any pretrained models in Pytorch/Tensorflow/Keras/fastai/... (you can also manually build your won model), and then report your accuracy, plot your training loss, validation loss, test loss, and plot your confusion matrix based on your test dataset. Please specify which one give yout the best result.

Please try/answer the following methods/questions: 
1 Please utilize cross-validation to tune your hyperparameters. Specify what hyperparameters you have tuned and how you tuned it.

2 Beause the number of images of latino and asian people are much less than the images of black indian and white people, the accuracy of predicting latin and asian prople is usually lower than the others. Please utilize weighting/bootstrap/anyother methods that can tackle this problem.

3 If your loss plot shows your model is overfitting, e.g. your validation loss is not stable, what methods will you try to solve it? Please specify them and show they do work.

4 Please multilable your lables and solve the overfitting problem (if there is one).
