## *Horse vs Human Classification With CNN* 
 
   •  Horse vs Human classifier which uses a dataset containing rendered images divided into two classes Horse & Human,
      A Convolutional neural network was trained using Tensorflow for 20 epochs which predicts whether the image uploaded by the user into the trained model is an              image of a horse or of a human.

# Convolutional Neural Network

In deep learning, a convolutional neural network is a class of deep neural networks, most commonly applied to analyzing visual imagery. They are also known as shift invariant or space invariant artificial neural networks, based on their shared-weights architecture and translation invariance characteristics.

# Getting the Data

• I have downloaded the Data and stored in a specific directories using following lines of code.

   tf.keras.utils.get_file('horse-or-human.zip',"https://storage.googleapis.com/laurencemoroney-blog.appspot.com/horse-or-human.zip")
   
# Looking the Data or Data Visualization
    
   • I have presented the 1 pictures of horses and 1 pictures of humans

# Convolutional Neural Network
 
 • In deep learning, a convolutional neural network is a class of deep neural networks, most commonly applied to analyzing visual imagery. They are also known as shift invariant or space invariant artificial neural networks, based on their shared-weights architecture and translation invariance characteristics.
Building Convolutional Neural Network from scratch using Tensorflow and Keras API.

•  Since it is a two class Classification problem i.e a Binary Classfication problem, I will use sigmoid activation so that the output of my network will be a single scalar between 0 and 1, encodig the probability of the images.

# Data Processing

• I have used ImageDataGenerator to perform Data Processing. I will process our images by normalizing pixel values in range of [0, 1] which is originally in range of [0, 255]

![2](https://user-images.githubusercontent.com/101402562/189898703-88540d22-9b43-4290-b7e4-cae0246c7131.png)




# Snapshot of the Model Summary
  
  ![Screenshot 2022-09-13 173553](https://user-images.githubusercontent.com/101402562/189898016-a12d8162-2ac3-4cbc-8738-1bfcac75a3be.png)
  
# Model Prediction

 • I have used the picture of horse and the model predicted horse, so the model is accurate in classification of human vs horse.

