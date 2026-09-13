# SpotifAI – Music Classification using Machine Learning

## Overview
SpotifAI is a machine learning project that analyzes Spotify track data and applies classification algorithms to identify patterns and relationships among various music features. The project demonstrates the complete machine learning workflow, from data preprocessing and exploratory data analysis to model training and evaluation.

## Dataset
The Spotify dataset consists of two files: `tracks.csv` and `artists.csv`. After initial exploration, `tracks.csv` was selected for model development due to the availability of relevant numerical features suitable for machine learning analysis.

## Project Workflow
- Cleaned and preprocessed the dataset by handling missing and duplicate values.
- Performed Exploratory Data Analysis (EDA) using histograms, boxplots, and correlation heatmaps.
- Analyzed relationships between different musical attributes.
- Detected and handled outliers using Z-Score and IQR methods.
- Trained and evaluated multiple classification models.
- Compared model performance using standard evaluation metrics and visualizations.

## Technologies Used
- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## Results
Among all the models tested, the **Random Forest Classifier** achieved the best performance.

- Accuracy: **86.8%**

Model performance was further analyzed using confusion matrices, correlation heatmaps, and accuracy comparison graphs.

### Confusion Matrix
<img width="500" alt="Confusion Matrix" src="https://github.com/user-attachments/assets/1880b85a-a25d-4204-bd92-7a940483178a" />

### Correlation Heatmap
<img width="600" alt="Correlation Heatmap" src="https://github.com/user-attachments/assets/f7f005fe-07f8-4308-841e-c2c23cab4b21" />

### Model Accuracy Comparison
<img width="600" alt="Model Accuracy Compariosn" src="https://github.com/user-attachments/assets/cc32eeec-a793-428a-92e2-5bf08e623be5" />

## Key Learning
This project helped me understand the complete machine learning pipeline, including data preprocessing, feature engineering, exploratory data analysis, model training, evaluation, and performance comparison.

## Future Scope
- Music Recommendation Systems
- Mood/Vibe Classification
- Genre Prediction
- Music Trend Forecasting

## Author
Vaibhavi Agarwal
