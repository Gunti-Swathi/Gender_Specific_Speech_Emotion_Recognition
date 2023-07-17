# Gender-Specific Speech Emotion Recognition
# Emotion Recognition App with Gender-Specific Acoustic Variance

## Description
The goal of this project is to develop an innovative mobile app capable of accurately recognizing emotional states by addressing acoustic variance between genders. We aim to achieve this by utilizing a gender-specific dataset and employing advanced machine learning and deep learning techniques.

### Dataset
We have assembled a comprehensive dataset that includes recordings from both male and female speakers. The SLR45 Database will serve as the foundation for gender identification using a Gaussian Mixture Model (GMM). Additionally, we have integrated several well-known emotion-specific datasets, namely RAVDESS, CREMA-D, SAVEE, and TESS, to train and validate our emotion recognition model.

### Feature Extraction
To capture essential information from the speech signals, we leverage Mel Frequency Cepstral Coefficients (MFCC) to extract relevant features like pitch, intonation, and prosody. This step is critical in ensuring that our model can effectively distinguish emotional cues unique to different genders.

### Gender Identification
The first stage of our emotion recognition pipeline involves accurately identifying the gender of the speaker. To achieve this, we employ a Gaussian Mixture Model (GMM), trained on the SLR45 Database, which allows us to reliably discern between male and female speakers.

### Emotion Recognition
In the second stage, we utilize deep learning classifiers, specifically Convolutional Neural Networks (CNNs), to perform emotion recognition. Our ensemble model is trained on a combination of RAVDESS, CREMA-D, SAVEE, and TESS datasets, providing it with a diverse range of emotional expressions for robust and accurate predictions.

### App Development
The final deliverable of this project is an intuitive and user-friendly mobile application that takes in speech input and accurately predicts the speaker's emotional state. The app will be developed for both Android and iOS platforms, allowing widespread accessibility and usage.

### Evaluation and Performance Metrics
Here we have used accuracy, confusion matrix, precision, and recall to evaluate the performance of our emotion recognition model. Accuracy will provide an overall measure of the model's correctness, while the confusion matrix will offer a detailed breakdown of its predictions for each emotion and gender class. Precision will assess the accuracy of positive predictions, while recall will measure the model's ability to identify all relevant emotions and genders effectively.  Through rigorous optimization and fine-tuning, we aim to create an accurate and robust emotion recognition app that considers gender-specific acoustic variance, contributing to a better understanding of emotions in various real-world scenarios. 

![Picture1](https://github.com/Gunti-Swathi/Gender_Specific_Speech_Emotion_Recognition/assets/75379302/d99c0412-84f7-4af7-89d9-29cadad464f9)
![Picture2](https://github.com/Gunti-Swathi/Gender_Specific_Speech_Emotion_Recognition/assets/75379302/dfaf47d5-8167-48f4-8e7f-296b5487bbd9)
