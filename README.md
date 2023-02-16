# Credit_Risk_Analysis

## Overview
In credit risk there is a challenge for classification, since good loans outnumber risky loans, therefore a model need to be built considereing unbalanced classes. By preparing data, statistical reasoning, and machine learning techniques, the analysis inteds to explore different models to predict risk (high/low). 

The following machine learning algorithms were used:
- RandomOverSampler (oversampling)
- SMOTE (oversampling)
- ClusterCentroids (undersampling)
- SMOTEENN (Over and Under sampling)
- BalancedRandomForestClassifier
- EasyEnsembleClassifier


## Results

For all the models, the following structure was followed:

- Split the Data into Training and Testing
- Create features and target
- Traing the model
- Test and predict
- Use Accuracy, Confussion matrix and f-1 score to evaluate the model.



### EasyEnsembleClassifier-1

- Accuracy : 92.6% 

![image](https://user-images.githubusercontent.com/114015620/218568969-53b0424d-2f1f-420e-b177-d8276c67cc2a.png)


- Confussion matrix

![image](https://user-images.githubusercontent.com/114015620/218569062-ae0e287c-e4b3-40ce-bc2f-f9b4e63de47b.png)


- Imbalanced classification report f1-score 0.97, high-risk 0.14

![image](https://user-images.githubusercontent.com/114015620/218569123-290511f0-5188-42eb-b015-51c03fd15ce8.png)

### BalancedRandomForestClassifier-2

- Accuracy 78.2%

![image](https://user-images.githubusercontent.com/114015620/218567180-f7b2f85a-541f-4264-a2d8-0d92b7d30d3c.png)

- Confussion matrix

![image](https://user-images.githubusercontent.com/114015620/218567231-0daafdb3-97b4-45ef-9011-653234cdce4f.png)


- Imbalanced classification report f1-score 0.94, high-risk 0.06

![image](https://user-images.githubusercontent.com/114015620/218567427-59c42834-5882-4bb8-a7c7-50dfedd7be00.png)

### RandomOverSampler (oversampling)- 3

- Accuracy 64.8%


<img width="439" alt="Screen Shot 2023-02-12 at 17 21 49" src="https://user-images.githubusercontent.com/114015620/218343439-b216196e-864f-4854-9579-963e79943533.png">

- Confussion matrix

<img width="376" alt="Screen Shot 2023-02-15 at 18 24 09" src="https://user-images.githubusercontent.com/114015620/219226262-fc1e6c1d-1a06-4a6d-9559-1790f2208e44.png">


- Imbalanced classification report f1-score 0.78, high-risk 0.02

<img width="663" alt="Screen Shot 2023-02-12 at 17 22 58" src="https://user-images.githubusercontent.com/114015620/218343494-51ccaee3-3c98-4015-89aa-e47ced8fa17d.png">



### SMOTE (oversampling) -4


- Accuracy 63.5%

![image](https://user-images.githubusercontent.com/114015620/218566353-4280b840-690d-4340-9483-56b42285feaf.png)

0.6481

- Confussion matrix

<img width="395" alt="Screen Shot 2023-02-15 at 18 07 20" src="https://user-images.githubusercontent.com/114015620/219223703-5d78a6ef-0a3f-4397-b2e6-9c13d6c76c4a.png">


- Imbalanced classification report f1-score 0.76, high-risk 0.02

![image](https://user-images.githubusercontent.com/114015620/218566536-22110974-e701-45e2-8e92-0be639f13fc0.png)

# SMOTEENN (Over and Under sampling)-5


- Accuracy 63.9%

![image](https://user-images.githubusercontent.com/114015620/218566645-f5a08a6a-7e9c-4550-bc01-94dee089d435.png)

- Confussion matrix

![image](https://user-images.githubusercontent.com/114015620/218566727-a191c576-97cb-46c6-be21-78ea9af7b3f8.png)


- Imbalanced classification report f1-score 0.72, high-risk 0.02

![image](https://user-images.githubusercontent.com/114015620/218566827-6d432c9a-5257-43df-b518-5c6710125a73.png)




### ClusterCentroids (undersampling)-6

- Accuracy 51.9%

![image](https://user-images.githubusercontent.com/114015620/218565965-28284217-fce4-4b28-bd24-eb9bc868e87d.png)


- Confussion matrix 

![image](https://user-images.githubusercontent.com/114015620/218566135-d396dc09-3900-4abd-940e-cae7b03740c5.png)


- Imbalanced classification report f1-score 0.61, high-risk 0.01

![image](https://user-images.githubusercontent.com/114015620/218566216-7e2431d9-409a-4f30-b4d9-9eb8beb6c2e3.png)


## Summary 

The models are ordered from the best model to the worst. In first place EasyEnsembleClassifier is found with an accuracy of 92.6%. Even when this may seem as a good score, the intention of the analysis was to find the customers' with high risk status, the best this model could achieve was 0.14. Through this analysis it is proven how unbalanced data plays a major role for model predictions. There is a high chance of commiting error Type II  ___.  




