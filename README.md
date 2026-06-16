# Income classification with bias and fairness analysis.

This project predicts whether an individuals income is greater than $50K per year based in demographic and employment attributes. Alongside model performance, the project includes a bias and fairness analysis to evaluate whether predictions were influenced by sensitive attiributes such as gender.

The fairness evaluation uses metircs including **disparate impact, demographic parity** and **equal opportunity** to asssess whether the models behave differenty across gender groups

Project objectives
- Clean and preprocess the dataset
- Apply appropriate statistical tsts to compare the relationships between variables and interpretthe results
- Build machine learning models to classify income levels
- Analyse model performance using standard evaluation metrics
- Compare the performance of the models before and after addressing class imbalance
- Assess fairness across gender groups using quantitative fairness metrics
- Interpret whether the model exhibits bias and how this may be addressed 

Libraries used
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Sklearn
- HolisticAI

Machine Learning models used
- Random Forest
- Logistic Regression
- Ada Boost
- Neural Network

Each model was evaluates using
- Confusion Matrix
- Precision
- Recall
- F1-score
- Accuracy
- ROC-AUC curves

Fairness was analysed using:
- Disparate impact
- Demographic parity
- Equal opportunity of difference

<br>These metrics help determine whether the models predictions disproportionately favour or disadvantage a particular gender group<br>

