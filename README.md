# Brain MRI Image Classification (Tumor vs Non-Tumor)

## Overview
This project uses a Convolutional Neural Network (CNN) to classify brain MRI images into tumor and non-tumor categories. The model is built using TensorFlow/Keras and includes preprocessing, augmentation, training, and evaluation.

## Dataset
The dataset contains MRI images labeled as **tumor** and **non-tumor**.  
Source: [Kaggle Brain MRI Dataset](https://www.kaggle.com)

*(Note: Raw images are not included in this repository due to size and licensing.)*

## Tech Stack
- Python
- TensorFlow / Keras
- pandas, NumPy
- matplotlib, seaborn
- scikit-learn

## Key Steps
- Loaded and preprocessed MRI images
- Applied data augmentation (rotation, zoom, flips)
- Built a CNN model using TensorFlow/Keras
- Trained and validated the model
- Evaluated accuracy, precision, recall, and confusion matrix
- Visualized training curves and predictions

## Results
- Achieved strong classification performance
- Clear separation between tumor and non-tumor classes
- Visualized confusion matrix and sample predictions

## Files
- `brain_mri_classification.ipynb` — full notebook

## Future Improvements
- Experiment with transfer learning (VGG16, ResNet50)
- Add Grad-CAM visualizations
- Deploy model as a simple web app
