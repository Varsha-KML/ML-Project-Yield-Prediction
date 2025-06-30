# ML-Project-Yield-Prediction
Objective:

Develop a Machine Learning-based classification model that can accurately predict whether a semiconductor unit will pass or fail during the manufacturing process, based on the collected data.

Works:

Data Loading and Initial Inspection:

Data Preprocessing:

     Analyzed the distribution of the target variable ('Pass/Fail'), noting a significant class imbalance.

     Addressed the class imbalance using the SMOTE technique to oversample the minority class.

     Split the resampled data into training and testing sets (80/20 split).

     Standardized the features using StandardScaler.

Exploratory Data Analysis (EDA):

     Examined summary statistics of the features.

     Visualized the distribution of sample sensor features using histograms.

     Calculated the correlation of each feature with the target variable and identified the top 10 most correlated features.

    Visualized the distribution of the top 10 correlated features against the target variable using boxplots.
    
Model Training and Evaluation:

    Trained and evaluated three different classification models:
    
    Random Forest Classifier
    
    Support Vector Machine (SVM)
    
    Gaussian Naive Bayes
    
    Evaluated each model using the classification report, which includes precision, recall, F1-score, and support.
    
Hyperparameter Tuning:

    Performed hyperparameter tuning on the Random Forest model using GridSearchCV to find the best parameters.
    
    Evaluated the best-performing Random Forest model.
    
Model Comparison and Saving:

    Compared the accuracy of all trained models.


