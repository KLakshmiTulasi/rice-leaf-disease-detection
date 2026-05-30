# Rice Leaf Disease Detection using Deep Learning

## Project Overview

Rice is one of the most important agricultural crops and is highly susceptible to various leaf diseases that can reduce crop productivity. This project uses Deep Learning and Computer Vision techniques to automatically detect and classify rice leaf diseases from images.

The project compares a custom Convolutional Neural Network (CNN) with a Transfer Learning approach using MobileNetV2 to determine the most effective model for disease classification.

---

## Problem Statement

Develop a machine learning solution capable of classifying rice leaf diseases into the following categories:

* Leaf Smut
* Brown Spot
* Bacterial Leaf Blight

The project also includes exploratory analysis, image preprocessing, data augmentation, model training, evaluation, and comparison.

---

## Dataset Information

* Total Images: 119
* Number of Classes: 3
* Image Format: JPG
* Dataset Type: Disease-infected rice leaf images

Classes:

1. Leaf Smut
2. Brown Spot
3. Bacterial Leaf Blight

---

## Technologies Used

* Python
* TensorFlow
* Keras
* MobileNetV2
* OpenCV
* NumPy
* Matplotlib
* Jupyter Notebook

---

## Project Workflow

1. Data Collection
2. Data Preprocessing
3. Data Augmentation
4. CNN Model Development
5. Transfer Learning using MobileNetV2
6. Model Training
7. Performance Evaluation
8. Model Comparison
9. Result Analysis

---

## Deep Learning Techniques Applied

### Data Augmentation

The following augmentation techniques were used:

* Rotation
* Zoom
* Horizontal Flip
* Rescaling

These techniques helped reduce overfitting and improve model generalization.

### Transfer Learning

MobileNetV2 with ImageNet pre-trained weights was used to improve classification performance on the limited dataset.

### Early Stopping

Early stopping was implemented to prevent overfitting and restore the best-performing model weights.

---

## Model Comparison

Two approaches were evaluated:

### CNN Model

* Built from scratch
* Learns features directly from dataset

### MobileNetV2 Transfer Learning

* Uses pre-trained ImageNet weights
* Faster convergence
* Better generalization on small datasets

---

## Results

* Successful classification of rice leaf diseases
* Data augmentation improved model robustness
* Transfer Learning outperformed the custom CNN model
* Overfitting was reduced using dropout and early stopping

---

## Challenges Faced

### Limited Dataset

The dataset contained only 119 images, increasing the risk of overfitting.

### Model Generalization

Limited training data made it difficult for models to generalize effectively.

### Class Representation

Small sample sizes required augmentation techniques to improve learning performance.

---

## Future Improvements

* Increase dataset size
* Use EfficientNet or ResNet architectures
* Hyperparameter tuning
* Deploy as a web application
* Real-time disease detection using mobile devices

---

## Conclusion

This project demonstrates the application of Deep Learning and Transfer Learning techniques for agricultural disease detection. MobileNetV2 achieved better performance compared to a traditional CNN and showed strong potential for practical deployment in smart agriculture solutions.
