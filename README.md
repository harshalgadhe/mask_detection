# Mask Detection

We will use MTCNN package to detect faces in a image and then feed all the faces detected to the nueral network to predict the cropped image into mask or no_mask class.
The data to train the model is taken from <a href='https://www.kaggle.com/andrewmvd/face-mask-detection'>Mask Detection</a> which consists of annotations and images. Custom Neural Network is used to train the network and the accuracy on train and test data is 94% on average.

As the size of 'model's weights' file exceeded it wasn't possible to upload it but you can get the weights by training the model directly as it takes onlu about 5 minutes to train the model on a GPU.
