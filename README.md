# Predicting Immunocompromise

## Motivation

In response to the COVID-19 pandemic and the need for better preparedness against infectious diseases, this project aims to predict the likelihood of immunosuppression in individuals. By leveraging machine learning techniques, we can identify those at higher risk and improve healthcare interventions.

## Data

The project utilizes data from The National Health Interview Survey (NHIS) for 2021, collected through personal household interviews covering various health topics. After careful cleaning and processing, relevant variables related to immunosuppression were extracted to create a binary dependent variable indicating immunosuppressed (1) or not immunosuppressed (0) individuals.

## Analytical Models

The project explores several classification models to predict immunosuppression:

1. **Baseline Model**: Predicts the majority value of the dependent variable.
2. **Logistic Regression**: Utilizes logistic function to predict probabilities of immunosuppression.
3. **Linear Discriminant Analysis (LDA)**: Uses linear combinations of features to classify.
4. **Decision Tree Classifier (DTC)**: Creates a tree structure for classification.
5. **Random Forest**: Ensemble of decision trees for improved accuracy.
6. **Gradient Boosting**: Builds models sequentially to correct errors of previous models.
7. **Vanilla Bagging**: Ensemble method using bootstrap samples.

Performance metrics such as accuracy, true positive rate (TPR), false negative rate (FNR), and cross-validation were used for model evaluation and selection. The DTC model was chosen as the best performer due to its balanced accuracy and TPR, crucial for medical applications.

## Impact

The project's impact extends to various areas:

1. **Healthcare Management**: Improved identification of immunosuppressed individuals leads to better care and monitoring by healthcare providers.
2. **Pandemic Preparedness**: Early identification of high-risk individuals aids in targeted interventions during pandemics, reducing transmission and mortality rates.
3. **Research and Development**: Insights from predictive modeling contribute to the development of new treatments and therapies for immunosuppression.
4. **Public Health Awareness**: Increased awareness and understanding of immunosuppression promote proactive health measures and education among the general population.

## References

- [National Health Interview Survey (NHIS) Data](https://ftp.cdc.gov/pub/Health_Statistics/NCHS/Datasets/NHIS/2021/adultinc21csv.zip)
- [NHIS Dataset Documentation](https://ftp.cdc.gov/pub/Health_Statistics/NCHS/Dataset_Documentation/NHIS/2021/adult-summary.pdf)
  
## Appendices

- [Appendix A: Ccp_alpha vs. Mean Validation TPR with CV on DTC]()
- [Appendix B: Decision Tree Associated with DTC Model]()
- [Appendix C: Accuracy and TPR Values for Different Threshold Values in Logistic Regression]()

