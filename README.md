# Abstract:-

This project aims to develop a Emotion Detection Using Facial expression recognition with the help of Convolutional Neural Networks (CNN). The primary objective is to accurately classify human emotions based on their facial expressions into multiple classes, such as happy, sad, angry, neutral, surprised, etc. The proposed system holds potential applications in various fields, including market research, customer feedback analysis, and human-computer interaction.

# Introduction:-

Emotion Detection is an essential area of research in artificial intelligence, focusing on understanding human emotions and opinions expressed through various mediums, such as text, speech, and images. In this project, we focus on facial expression recognition as a modality to analyse emotions. The use of deep learning techniques, specifically, Convolutional Neural Networks, has shown significant improvements in image-based classification tasks, making it an ideal choice for this project.
Our goal is to create a deep learning-based model for face emotion analysis. Using a convolutional network architecture(CNN), face characteristics can help to classify emotions into Disgust, Fear, Anger, Surprise, Happiness, Sadness, and Neutral. In a typical neural network with data augmentation, is used to recognize face expressions. This method can categorize images into Anger, Disgust, Fear, Happy, Sad, Surprise, and Neutral. Due to their huge number of filters available, CNNs are considered superior for image identification tasks. 

# Dataset:-

The project utilizes a ‘publicly’ available facial expression dataset from Kaggle containing labelled facial images corresponding to various emotions. The dataset is pre-processed to ensure uniformity and standardization of the images before feeding them into the CNN model, for the real time detection.
This dataset helps in providing with a large number of images for training our deep learning model for future predictions of facial emotions and implementing the model for making predictions in the real time.
The dataset can further be improved by adding more number of related images with impoverished quality which could enhance the efficiency of this facial emotion recognition model, and would help in recognising emotions in real time even for a large group of people.

# Convolutional Neural Network Architecture:
The CNN model is designed to perform multi-class classification for facial expression recognition. The architecture typically consists of multiple convolutional layers, followed by pooling layers, and then fully connected layers.
  * Convolutional layers: These layers are responsible for learning feature representations from the input images. Multiple convolutional filters are applied to extract various patterns.
  * Pooling layers: After each convolutional layer, pooling layers help reduce the spatial dimensions, down sampling the feature maps and retaining the essential information.
  * Fully connected layers: The last layers of the CNN convert the extracted features into probabilities for each emotion class through a series of dense layers.

