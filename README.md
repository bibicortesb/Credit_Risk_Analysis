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
- Test

### RandomOverSampler (oversampling)
- Accuracy 


<img width="439" alt="Screen Shot 2023-02-12 at 17 21 49" src="https://user-images.githubusercontent.com/114015620/218343439-b216196e-864f-4854-9579-963e79943533.png">

- Confussion matrix

<img width="495" alt="Screen Shot 2023-02-12 at 17 22 21" src="https://user-images.githubusercontent.com/114015620/218343477-2376dfad-3665-43f0-97b1-4519e95ceba0.png">

- Imbalanced classification report

<img width="663" alt="Screen Shot 2023-02-12 at 17 22 58" src="https://user-images.githubusercontent.com/114015620/218343494-51ccaee3-3c98-4015-89aa-e47ced8fa17d.png">



### SMOTE (oversampling)


- Accuracy 

![image](https://user-images.githubusercontent.com/114015620/218566353-4280b840-690d-4340-9483-56b42285feaf.png)

- Confussion matrix

![image](https://user-images.githubusercontent.com/114015620/218566429-c4c9f3e2-ef32-466c-9126-a12040b0a077.png)

- Imbalanced classification report

![image](https://user-images.githubusercontent.com/114015620/218566536-22110974-e701-45e2-8e92-0be639f13fc0.png)



### ClusterCentroids (undersampling)

- Accuracy 

![image](https://user-images.githubusercontent.com/114015620/218565965-28284217-fce4-4b28-bd24-eb9bc868e87d.png)


- Confussion matrix

![image](https://user-images.githubusercontent.com/114015620/218566135-d396dc09-3900-4abd-940e-cae7b03740c5.png)


- Imbalanced classification report

![image](https://user-images.githubusercontent.com/114015620/218566216-7e2431d9-409a-4f30-b4d9-9eb8beb6c2e3.png)


# SMOTEENN (Over and Under sampling)


- Accuracy 

![image](https://user-images.githubusercontent.com/114015620/218566645-f5a08a6a-7e9c-4550-bc01-94dee089d435.png)

- Confussion matrix

![image](https://user-images.githubusercontent.com/114015620/218566727-a191c576-97cb-46c6-be21-78ea9af7b3f8.png)


- Imbalanced classification report

![image](https://user-images.githubusercontent.com/114015620/218566827-6d432c9a-5257-43df-b518-5c6710125a73.png)


# BalancedRandomForestClassifier

- Accuracy 

![image](https://user-images.githubusercontent.com/114015620/218567180-f7b2f85a-541f-4264-a2d8-0d92b7d30d3c.png)

- Confussion matrix

![image](https://user-images.githubusercontent.com/114015620/218567231-0daafdb3-97b4-45ef-9011-653234cdce4f.png)


- Imbalanced classification report

![image](https://user-images.githubusercontent.com/114015620/218567427-59c42834-5882-4bb8-a7c7-50dfedd7be00.png)



# EasyEnsembleClassifier

- Accuracy 
- 

- Confussion matrix


- Imbalanced classification report



## Summary 
