# credit-risk-analysis

## Overview
Utlizing machine learning to determine credit risk based on various factors related to previous loan applications. 

## Results

### Oversampling

#### Naive Random Oversampling
##### Classification Report
![Naive Random Oversampling](Resources/Images/naive_random_class.png)
##### Balanced Accuracy Score
0.6631475238262834 &rarr; 66.3%
</br></br>
#### SMOTE Oversampling
##### Classification Report
![SMOTE Oversampling](Resources/Images/smote_class.png)
##### Balanced Accuracy Score
0.6419006844557233 &rarr; 64.2%
</br></br>
### Undersampling

##### Classification Report
![Cluster Centroids](Resources/Images/cluster_class.png)
##### Balanced Accuracy Score
0.5451813715047837 &rarr; 54.5%
</br></br>
### Comination Over/Undersampling (SMOTEENN)
##### Classification Report
![SMOTEENN](Resources/Images/smoteenn_class.png)
##### Balanced Accuracy Score
0.6550612907408608 &rarr; 65.5%
</br></br>
### Ensembles 

#### Balanced Random Forest Classifier
##### Classification Report
![Balanced Random Forest Classifier](Resources/Images/brfc_class.png)
##### Balanced Accuracy Score
0.6830221521918328 &rarr; 68.3%
</br></br>
#### Easy Ensemble AdaBoost Classifier
##### Classification Report
![Easy Ensemble AdaBoost Classifier](Resources/Images/eeac_class.png)
##### Balanced Accuracy Score
0.9316600714093861 &rarr; 93.1%


## Summary
There is a summary of the results
There is a recommendation on which model to use, or there is no recommendation with a justification