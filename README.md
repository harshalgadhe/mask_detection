# Mask Detection

We will use MTCNN package to detect faces in a image and then feed all the faces detected to the nueral network to predict the cropped image into mask or no_mask class.
The data to train the model is taken from <a href='https://www.kaggle.com/andrewmvd/face-mask-detection'>Mask Detection</a> which consists of annotations and images. Custom Neural Network is used to train the network and the accuracy on train and test data is 92% on average.

To increase the accuracy and model's performace you can add more images in the dataset and using Transfer Learning can also boost the model's accuracy further.

You can use the model to predict in real time by using the code <a href='https://github.com/harshalgadhe/mask_detection/blob/main/Code%20for%20Using%20the%20Model%20in%20Real%20Time'>Real Time Detection </a>. You can use this code in any local python ide which supports using your camera. I have used Pycharm to use the model in real time.

You can also download my model's weight from the <a href='https://drive.google.com/file/d/1byLffn_7gWxHpRa3d1TlsNiE9s7_feQU/view'>Google Drive</a>. Additionally you would need to install libraries such as keras, cv , mtcnn in your python ide.

<img src='https://github.com/harshalgadhe/mask_detection/blob/main/Mask%20Detection.png'>
