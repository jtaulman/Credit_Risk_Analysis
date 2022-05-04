# Credit_Risk_Analysis

## Overview
The goal for this challenge is to incorporate a machine learning model to predict credit risk from a Loanstats csv file. The data will be imported, resampled and evaluated through a supervised machine learning model.

## Analysis

### Naive Random Oversampling

![Naive Oversampling](https://user-images.githubusercontent.com/95730434/166623483-aceba976-e5cd-4d58-bc09-0fd4aa74b50c.png)

### SMOTE Oversampling

![SMOTE Oversampling](https://user-images.githubusercontent.com/95730434/166623486-9e082356-5c6f-4e55-bcf8-5ea1d7f5b85d.png)

### Undersampling

![Undersampling](https://user-images.githubusercontent.com/95730434/166623495-695355d2-b19e-4aa4-87be-703769dc61b7.png)

### Combination Sampling

![Combination Sampling](https://user-images.githubusercontent.com/95730434/166623498-713852e5-6d80-465d-9957-6f714762dc94.png)

## Summary

![Summary 1](https://user-images.githubusercontent.com/95730434/166623507-255e1bb3-5263-4cf3-89d9-2c7ad907d217.png)

### Balanced Random Forest Classifier

![Balanced Random Forest](https://user-images.githubusercontent.com/95730434/166623510-e9f0dea3-a72d-492d-bc20-2457ac6fb977.png)

### Easy Ensemble AdaBoost Classifier

![Easy Ensemble AdaBoost](https://user-images.githubusercontent.com/95730434/166623517-c4cc1f42-e46f-4dec-aa45-7cc3a7a5b434.png)

## Summary

![Summary 2](https://user-images.githubusercontent.com/95730434/166623521-a39575d8-80be-4200-a649-808b40609297.png)

## Conclusion

After running the data through the six different models, the Easy Ensemble AdaBoost Classifier performs the best and therfore should be used for further analysis. This is due to the extremely high Balanced Accuracy Score and Recall in comparison to the other models. This model would do the best job of preventing False Negative results.