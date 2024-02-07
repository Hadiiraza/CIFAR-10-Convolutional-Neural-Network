# CIFAR-10-Convolutional-Neural-Network

## Project Overview:
This project involves building and training a Convolutional Neural Network (CNN) using the CIFAR-10 dataset. The CIFAR-10 dataset consists of 60,000 32x32 color images in 10 different classes, with 6,000 images per class.

## Dataset Description:
The CIFAR-10 dataset contains color images belonging to ten classes: airplanes, cars, birds, cats, deer, dogs, frogs, horses, ships, and trucks. Each image is of size 32x32 pixels and belongs to one of the ten categories.

## Data Preprocessing:
- Loading Dataset: The CIFAR-10 dataset is loaded using the Keras library.
- Normalization: Pixel values of the images are normalized to a range between 0 and 1 by dividing by 255.
- Categorical Encoding: The target labels are converted into a categorical format using one-hot encoding.

## Model Building and Training:
- Convolutional Neural Network (CNN): A CNN architecture is constructed using layers such as Conv2D, MaxPooling2D, Flatten, and Dense.
- Model Compilation: The CNN model is compiled using categorical cross-entropy loss and the RMSprop optimizer.
- Model Training: The CNN model is trained on the training set for multiple epochs.

## Model Evaluation:
- Predictions: The trained model is used to make predictions on the test set.
- Classification Report: A classification report is generated, showing metrics such as precision, recall, and F1-score for each class.
- Accuracy: The overall accuracy of the model is calculated based on the predictions.

## Conclusion:
The trained CNN model demonstrates its ability to classify images from the CIFAR-10 dataset with a reasonable level of accuracy. Further optimizations and fine-tuning may be explored to improve the model's performance.
