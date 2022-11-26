# Credit_Risk_Analysis

## Overview of the Analysis:

Determining if a person has a high or low credit risk can become very difficult to predict. In this project I am trying to create a model, train it and evaluate its result to try and predict a persons credit risk. This is a process used by data analyst in order to try and predict possible outcomes using past data. I used different methods such as oversampled the data using randomoversampler, smote algorithms and undersample data with the clustercentroid algorithmwhich will be shown on the results secction. Each learning model had different but intresting results from one another. 

## Results:

### Naive Random Oversampling: 

- Accuracy: 65% 
- Precision: 1%
- Recall: 72%

<img width="1002" alt="Naive Random Oversampling" src="https://user-images.githubusercontent.com/108498940/204070280-afc32764-5dfa-4a50-b657-115b7f23302a.png">

### SMOTE oversampling: 

- Accuracy: 66.2% 
- Precision: 1%
- Recall: 69%

<img width="1004" alt="SMOTE oversampling" src="https://user-images.githubusercontent.com/108498940/204070311-32fcf09c-0f00-4800-8567-b6765f0f091c.png">

### Undersampling:

- Accuracy: 66.2% 
- Precision: 99%
- Recall: 40%

<img width="1019" alt="Undersampling" src="https://user-images.githubusercontent.com/108498940/204070355-b568aca6-8363-4c6c-ab3e-f828381d0d68.png">

### Combination(over and undersampling):

- Accuracy: 66.2% 
- Precision: 99%
- Recall: 69%

<img width="989" alt="Combination" src="https://user-images.githubusercontent.com/108498940/204070394-7ccb9c39-0e0d-408a-b3d2-365e2f6bd427.png">

### Balanced Random Forest Classifier:

- Accuracy: 77.2% 
- Precision: 99%
- Recall: 88%

<img width="1015" alt="Balanced Random Forest Classifier" src="https://user-images.githubusercontent.com/108498940/204070411-5af68716-f08e-428d-8761-4f5ca1454335.png">

### Easy Ensemble AdaBoost Classifier:

- Accuracy:  91.7% 
- Precision: 99%
- Recall: 94%

<img width="1002" alt="Easy Ensemble AdaBoost Classifier" src="https://user-images.githubusercontent.com/108498940/204070422-8bfce2dc-c08a-4c43-b1ba-817c3f9bfdd9.png">



## Summary:

On the first models we got a really low accuracy test result which is not great for a predicting model like this one. In case of using this models there would not be a lot of successful predictions of high risk credit which would have a negative impact. Normaly in models like this ones it is great to have balance between precision and recall as well as a high accuracy score. Because of this my recomendation would be to use the Easy Ensemble AdaBoost Classifier since it has the best overall results. 

