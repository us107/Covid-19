# COVID-19 Detection Using CNN Through Chest X-Ray Images

## Overview
This repository contains the implementation of a Convolutional Neural Network (CNN) model to detect COVID-19 using chest X-ray images. The project demonstrates how deep learning techniques can assist in identifying COVID-19 cases with high accuracy.

## Purpose
This project was a group assignment for our *Machine Learning* subject. It highlights the application of CNNs in medical image analysis and aims to provide a foundation for further research and improvements in AI-based diagnostic tools.

## Team Members
- *Trisha Sharma* (229309215)
- *Anahita Bhandari* (229309186)

## Dataset
The model was trained and tested on a dataset containing chest X-ray images categorized into COVID-19 positive, normal, and pneumonia cases. The dataset was preprocessed to ensure compatibility with the CNN model.

## Methodology
1. *Data Preprocessing*: 
   - Resized images for uniformity.
   - Normalized pixel values for faster convergence.
   - Split the data into training, validation, and test sets.

2. *Model Architecture*:
   - Built a CNN with multiple convolutional and pooling layers.
   - Used ReLU activation and dropout for better generalization.
   - Added fully connected layers to classify images.

3. *Training*:
   - Optimized the model using the Adam optimizer.
   - Categorical cross-entropy as the loss function.
   - Evaluated model performance using accuracy and loss metrics.

4. *Testing*:
   - Assessed the model on unseen test data.
   - Generated a confusion matrix to analyze classification results.

## Results
- Achieved a high level of accuracy in classifying COVID-19 cases.
- The model demonstrated the potential of CNNs in medical diagnostics.

## How to Run the Project
1. Clone the repository:
   ```bash
   git clone https://github.com/<your-username>/covid19-detection-cnn.git
2. Install Requirements:
   pip install -r requirements.txt
- Atlast train and test the model

## Technologies Used
- *Python*
- *TensorFlow/Keras*
- *OpenCV*
- *NumPy, **pandas*
- *Matplotlib* for visualization

## Acknowledgments
This project was submitted as part of the coursework for our *Machine Learning* subject.  
We extend our gratitude to our faculty and peers for their guidance and support.
