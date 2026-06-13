# Alzheimer's Disease Detection using Machine Learning

This project aims to develop machine learning models to classify Alzheimer's disease based on MRI images. The dataset consists of MRI images of patients classified into four categories: Non-Demented, Very Mild Demented, Mild Demented, and Moderate Demented.

## Project Structure

- **`alzheimers_detection.ipynb`**: Jupyter Notebook containing the Python code for data preprocessing, model training, evaluation, and visualization.
- **`results/`**: Directory containing evaluation results, such as accuracy scores, confusion matrices, and classification reports.
- **`project_schematic/`**: Gives the flow of the project about how the data has been preprocessed, augemented and the different models applied.
- **`report/`**: Gives explanation to all the models applied on the dataset along with satisfactory evaluation metrics comparing the accuracy and loss for each model.
  

## Project Schematic

1. **Data Preprocessing**:
   - MRI images from the dataset are grayscaled and preprocessed using Prinicipal Component Analysis.
   - Data augmentation techniques such as brightness adjustment and adding Gaussian noise are applied to enhance the training dataset.

2. **Model Training**:
   - Various machine learning models are trained using the preprocessed MRI images.
   - Models include Convolutional Neural Network (CNN), Multiclass Logistic Regression, Decision Tree, and Random Forest.

3. **Model Evaluation**:
   - Trained models are evaluated using various evaluation metrics:
     - Accuracy: Overall accuracy of the model in classifying Alzheimer's disease.
     - Confusion Matrix: Visualization of model predictions compared to actual labels.
     - Classification Report: Detailed metrics such as precision, recall, and F1-score for each class.

4. **Results Visualization**:
   - Evaluation results are visualized using plots such as loss vs. epoch and accuracy vs. epoch for CNN models.
   - Confusion matrices and other visualizations are generated to analyze model performance.

## Setup and Installation

1. **Clone the repository:**

```bash
git clone https://github.com/your-username/alzheimers-detection.git
```

2. **Download the Dataset**

Load the dataset from the online Kaggle platform : [Dataset Link](https://www.kaggle.com/datasets/sachinkumar413/alzheimer-mri-dataset)

3. **Run the Jupyter Notebook:**
```bash
jupyter notebook alzheimers_detection.ipynb
```


# Contributors

- Aarya Khandelwal
- Aaradhya Verma
