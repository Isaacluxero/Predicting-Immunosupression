# Predicting Immunocompromise

## Motivation

In response to the COVID-19 pandemic and the need for better preparedness against infectious diseases, this project aims to predict the likelihood of immunosuppression in individuals. By leveraging machine learning techniques, we can identify those at higher risk and improve healthcare interventions.

## Data

The project utilizes data from The National Health Interview Survey (NHIS) for 2021, collected through personal household interviews covering various health topics. After careful cleaning and processing, relevant variables related to immunosuppression were extracted to create a binary dependent variable indicating immunosuppressed (1) or not immunosuppressed (0) individuals.

## Analytical Models

The project explores several classification models to predict immunosuppression, including logistic regression, decision tree classifier (DTC), random forest, and gradient boosting. Performance metrics such as accuracy and true positive rate (TPR) were used for model evaluation.

The DTC model emerged as the best performer, striking a balance between accuracy and TPR, making it suitable for medical applications where minimizing false negatives is critical.

## Impact

The project's impact includes improved identification of immunosuppressed individuals, leading to better healthcare management and preparedness for pandemics. Future extensions may involve incorporating additional data sources and exploring advanced modeling techniques.

## References & Appendices

- [Dataset and Variable Summary](https://ftp.cdc.gov/pub/Health_Statistics/NCHS/Datasets/NHIS/2021/adultinc21csv.zip)
- [Google Colab Notebook](https://colab.research.google.com/drive/1QRub_B-1m0QBm3VtrnNlhOQtfSCCIJ-L?usp=sharing)
- [Appendix A: Ccp_alpha vs. Mean Validation TPR with CV on DTC](#)
- [Appendix B: Decision Tree Associated with DTC Model](#)
- [Appendix C: Accuracy and TPR Values for Different Threshold Values in Logistic Regression](#)
