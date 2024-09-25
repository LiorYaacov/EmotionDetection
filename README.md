# Emotion Detection from Facial Expressions

## Project Introduction
This project aims to develop a deep learning model that accurately detects emotions from facial expressions in images. The model will recognize a range of emotions, including happiness, sadness, anger, fear, surprise, disgust, and neutrality.
![image](https://github.com/user-attachments/assets/8c3a60ba-e897-4a87-817b-ec6cbff94c2c)

## Problem Definition
The primary goal is to classify grayscale images of size (48, 48) into different emotional categories using a Convolutional Neural Network (CNN).

## Data
The model is trained on a large dataset of labeled images sourced from Kaggle's [Emotion Detection database](https://www.kaggle.com/datasets/ananthu017/emotion-detection-fer/data).
The dataset contain 35,685 examples of 48x48 pixel gray scale images of faces divided into train and test dataset. Images are categorized based on the emotion shown in the facial expressions (happiness, neutral, sadness, anger, surprise, disgust, fear).

Dataset Distribution:
- **Training images:** 28,709
- **Testing images:** 7,178



### Classes
The dataset includes the following emotion classes:
- Angry
- Disgusted
- Fearful
- Happy
- Neutral
- Sad
- Surprised

## Approach
The project involves several key steps:

1. **Data Import and Preprocessing:** Utilizing PyTorch DataLoaders to import and preprocess the images.
   
2. **Model Architecture:** Designing and implementing a deep learning CNN.

3. **Training and Validation:** Training the model on the preprocessed dataset, evaluating its performance, and tuning hyperparameters to optimize accuracy.

4. **Testing and Evaluation:** Testing the model on a separate dataset and evaluating its performance using accuracy metrics.

5. **State-of-the-Art (SOTA) Architectures:** Exploring and training state-of-the-art architectures to compare their performance.

## Benchmark
We will evaluate our model's performance by comparing it to other projects using the same dataset on Kaggle. Leading models have achieved accuracies around 65%, and our goal is to exceed these results on validation and test datasets.

### References
- [Kaggle Emotion Detection Dataset](https://www.kaggle.com/datasets/ananthu017/emotion-detection-fer/code)
- Most Voted Models:
  - [Model #1](https://www.kaggle.com/code/odins0n/emotion-detection)
  - [Model #2](https://www.kaggle.com/code/aayushmishra1512/emotion-detector)
  - [Model #3](https://www.kaggle.com/code/sanya9/emotion-detection-using-alexnet)
  - [Model #4](https://www.kaggle.com/code/sonyd4d/cnn-for-emotion-detection)
