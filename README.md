# PHAS0077- Emotion Classification of Speech Audio

Environment:Python 3.6 or Conda 4.10

# Dependencies
matplotlib for plot  
sklearn.metrics for confusion_matrix, classification_report, accuracy_score, auc  
sklearn.model_selection for GridSearchCV, cross_val_score, train_test_split

# Datasets
Sample_entertaining.csv for entertaining emotion classification  
Features extracted from YAMNeT network frame  


Sample_discussion.csv for discussion emotion classification  
Features extracted from eGeMAPS

# Classification model
Classifier_entertaining.ipynb  
Classifier_discussion.ipynb

# Usage
Run Classifier_entertaining.ipynb to conduct the entertaining emotion classification with Decision Tree, Rancom Forest and SVM  
Run Classifier_discussion.ipynb to conduct the discussion emotion classification with Decision Tree, Rancom Forest and SVM
