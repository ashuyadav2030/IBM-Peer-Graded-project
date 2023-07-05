# Image-Classification

My project aims to develop an image classification system for popular personality identification. Throughout the project, I follow a series of steps in order to achieve this goal.

    Objective:  The objective of the project is to accurately classify images of sports celebrities by leveraging machine learning techniques.

    Importing Libraries: I start by importing the necessary libraries and frameworks that will be used throughout the project.

    Data Preprocessing: The first step in data preprocessing is to ensure that the images are properly rendered, ensuring their quality and integrity. Additionally, I employ the Haar cascades technique to detect faces and eyes in the images, which serves as a crucial step in the subsequent analysis.

    Feature Extraction: To extract meaningful features from the images, I apply wavelet transformation. This technique helps in capturing relevant information that can aid in accurate image identification.

    Dataset Handling: I develop code to handle the dataset, including image cropping and storage of cropped images in a designated folder. This process helps in isolating the essential regions of interest within the images.

    Feature Matrix and Labels: I prepare the feature matrix (X) and the corresponding target labels (y) for the image classification task. This ensures that the data is properly structured for training and evaluation.

    Model Building: I split the dataset into training and testing sets, and proceed to evaluate the performance of the Support Vector Machine (SVM) algorithm. By experimenting with different hyperparameters, I aim to find the optimal SVM model that achieves high accuracy in classifying sports celebrity images.

    Model Evaluation: I use evaluation metrics such as the confusion matrix to assess the performance of the trained model. This helps in understanding the classification errors and the overall effectiveness of the model.

    Model Persistence: The best-performing SVM model is saved using the pickle library, allowing for future use and deployment in a production environment.

    Class Dictionary Conversion: To facilitate the interpretation of the model's predictions, I convert the class dictionary into JSON format, making it easier to map class labels to sports celebrities.

By following these steps, my project successfully develops an image classification system for sports celebrity identification. The project showcases my proficiency in data preprocessing, feature engineering, model selection, evaluation, and model deployment.
