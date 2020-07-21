This challeng is to test candiates capability to categorize facial images into different races and gender. 

The Dataset has 15805 images which are catcategorized into 10 folders: asianman, asianwoman, blackman, blackwoman, indianman, indianwoman, latinoman, latinowoman, whiteman and whitewoman. 

Please build classification models based on any pretrained neural network models in Pytorch/Tensorflow/Keras/fastai/... (you can also manually build your won model), and then report your accuracy, plot your training loss, validation loss, test loss, and plot your confusion matrix based on your test dataset. Please specify which one gives you the best result.

Please try/answer the following methods/questions: 

1 Please utilize cross-validation to tune your hyperparameters. Specify what hyperparameters you have tuned and how you tuned it.

2 Because the number of images of latino and asian people are much less than the images of black indian and white people, the accuracy of predicting latin and asian prople is usually lower than the others. Please utilize weighting/bootstrap/anyother method that can tackle this problem and show your improvement.

3 If your loss plot shows your model is overfitting, e.g. your validation loss is not stable, what method will you try to solve it? Please specify them and show how they work.

4 Please multilable your responses and solve the overfitting problem (if there is one).

5 Please try to extract linkedin profile images, categorize them using the best prediction model that you have just train and show your accuracy. (Bonus)  


To submit the challenge, please put your work in a jupyter notebook where you explain the solving process from preparing the data, modelling, visualizing and interpreting your results, and then email us the link to it. Thank you.
