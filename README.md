# Churn Prediction Project

## Overview

This project focuses on predicting customer churn for a business, helping to proactively identify and retain at-risk customers. The project aims to develop a robust model that prioritizes recall to maximize customer retention and ensure long-term business success.

Dataset on <a href= "https://www.kaggle.com/datasets/yeanzc/telco-customer-churn-ibm-dataset"> Kaggle</a>.

## Project Workflow

1. **Exploratory Data Analysis (EDA)**
    - Performed exhaustive EDA to understand the dataset.

2. **Baseline Model**
    - Built a baseline Logistic Model which yielded very poor results.

3. **Addressing Imbalance**
    - Understood the issue of the imbalanced target variable.
    - Performed oversampling (SMOTE) to overcome this issue.

4. **Model Building**
    - Built three models: SVC, RandomForestClassifier, and XGBoostClassifier.
    - Chose SVC as it yielded the highest recall with at par ROC-AUC score and F1-score.

5. **Model Evaluation**
    - Evaluated the models based on recall, precision, F1-score, and ROC-AUC score.
    - Selected the final model prioritizing recall due to the higher cost of acquiring new customers compared to retaining existing ones.

## Results

- **Final Model:** SVC
- **Performance Metrics:**
    - F1-Score: 84%
    - Accuracy: 84%
    - Recall: 83%

## Key Features

- Comprehensive EDA to uncover insights from the dataset.
- Handling class imbalance using SMOTE.
- Evaluation and comparison of multiple machine learning models.
- Focus on recall to ensure maximum customer retention.

## Project Significance

This project is a crucial step towards understanding and implementing machine learning techniques in real-world scenarios. It showcases the ability to derive meaningful insights and actionable strategies from data, emphasizing the importance of customer retention for business success.

## Technical Skills Demonstrated

- **Python** for data manipulation and model building.
- **Pandas** for data analysis and manipulation.
- **Scikit-learn** for machine learning algorithms.
- **Plotly** for creating interactive visualizations.

## Author

**Sougat Dey**

- Aspiring Data Scientist with a solid background in Python and Statistics.
- Proficient in Machine Learning and SQL.
- Experienced in building supervised and unsupervised machine learning projects.

## License

This project is unlicensed.

## Contact

Feel free to reach out for any queries or collaborations:

- **Email:** [to.sougatdey@gmail.com](mailto:to.sougatdey@gmail.com)
- **LinkedIn:** [Sougat Dey](https://www.linkedin.com/in/sougat-dey/)
