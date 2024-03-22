# Product-Image-Classifier
DL Model to classify images to {Beauty, Fashion, Home, Nutrition, Stationary} products.
This was a task given for an internship purpose.
Building the model :
1) I had a problem with the dataset as i have been told to screenshot the products images from the app, so i have downlaoded some of the iamges online to help the model to preform better preformance.
2) My dataset is consisting of train and test folders, inside each folder (Beauty, Fashion, Home, Nutrition, Stationary) folders, I separated them to be the training set ≃ 70% of the data And the testing set ≃ 20% of the data.
3) Defined this problem as Multi class single label classification problem.
4) To help the model preform better and as our data isn't big enough I made Image Augmentation to prevent overfitting. it will gives some random transformation on a random selection on our images like (rotation , flipping, ...) so we get more divers image.
5) I made a CNN of four convolution layers and after each layer a max pooling layer, then a flatten layer to suits it in the full connection layer, then a dense layer of 128 dim then another dense layer of 5 dim with an activation function of softmax
6) Trained the model and it gives me an accuracy of 86%

ToDo:
1) Increase our data
2) Make our problem a multi class multi label as in each class we make classes. ie fashion(hoodies,shirts,jeans)
3) Use a pretrained model like Resnet,Yolo,Inceptionv3
4) Fine tune the model of the data
5) Deploy on a website
