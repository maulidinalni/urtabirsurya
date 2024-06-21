**Description**
"Your Tabir Surya" application is a cloud-based Android application that uses machine learning to classify facial skin types and provide sunscreen product recommendations. This application utilizes Convolutional Neural Network (CNN) and transfer learning with Inception model to produce accurate classification and relevant product recommendations.

**Application of Machine Learning**
CNN and Transfer Learning Model
This application uses Convolutional Neural Network (CNN) and transfer learning with Inception model for facial skin type classification. The Inception model was chosen for its ability to handle complex image classification with high accuracy.

**Training Process**
1. Data Collection:
   - Collected a dataset of facial images with various skin types.
   - These datasets are divided into training set and testing set.

2. Data Preprocessing:
   - Images are resized to a size that matches the input of the Inception model.
   - Normalization of image pixels was done to speed up the convergence of the model.

3. Transfer Learning with Inception Model:
   - Using the Inception model pre-trained on the ImageNet dataset.
   - Customized the final layer of the model to classify facial skin types.
   - Model refinement is done with the collected dataset.

4. Model Training:
   - The model is trained using the training dataset.
   - Evaluation is performed using the testing dataset to determine
   - Hyperparameter tuning is performed to optimize model performance.
   - Implementation in Android App

**Model Deployment:**
The trained models are hosted on Google Cloud Platform (GCP) to ensure fast and efficient data processing.
The Android app communicates with the hosted model through an API.

**Classification Process:**
Users upload an image of their face through the app.
The image is sent to the server for processing by the CNN model.
The model classifies the skin type of the face and returns the results to the app.
The trained models are hosted on Google Cloud Platform (GCP) to ensure fast and efficient data processing.
The Android app communicates with the hosted model through an API.

**Classification Process:**
Users upload an image of their face through the app.
The image is sent to the server for processing by the CNN model.
The model classifies the skin type of the face and returns the results to the app.
