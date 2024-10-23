# Food Classification with Machine Learning

### Overview
This project focuses on classifying images of food as **healthy** or **unhealthy** using various machine learning models. The dataset is manually collected, consisting of labeled images where healthy food includes visible fruits and vegetables, and unhealthy food consists of processed or high-fat items.

### Key Features
- **Dataset**: 
  - Contains two categories: **healthy** (label 0) and **unhealthy** (label 1).
  - Each category has 30 manually labeled images.
  
- **Models Used**:
  - **Logistic Regression**: Evaluated using both basic train/test splitting and RGB feature extraction.
  - **Support Vector Machines (SVM)**: Explored both linear and non-linear versions.
  - **Convolutional Neural Networks (CNN)**: Being considered to improve performance over simpler models.

### Image Preprocessing
- Images were flattened to a 1D array for initial models using this transformation:

- RGB feature extraction was performed to enhance model performance with basic machine learning classifiers.

### Model Performance
Logistic Regression outperformed SVM in this classification task.
SVM showed poorer performance, likely due to the limited size and complexity of the dataset.

### Future Directions 
Implementing Convolutional Neural Networks (CNN) to handle image classification more effectively.
Exploring data augmentation to increase dataset size and variety.
Tuning hyperparameters and experimenting with different architectures for CNN.

### Tools & Libraries
- Python
- Scikit-learn for Logistic Regression and SVM
