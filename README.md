# Pedotan-MachineLearning
# 🌱 PEDOTAN (Pengendalian Optimal Tanaman) 🌿 - Guardians of the Green (Team C23-PS379) - ML Repository

Pedotan Machine Learning Repository for Bangkit Capstone Project. Building Machine Learning Model to identify plant disease 
## 👥Guardian of Machine Learning Bangkit Academy Capstone Team C23-PS379
|            Member           | Student ID |        Path        |                    Role                    |                                                       Contacts                                                      |
| :-------------------------: | :--------: | :----------------: | :----------------------------------------: | :-----------------------------------------------------------------------------------------------------------------: |
| Akbar Sigit Putra  | M169DSX0378 |  Machine Learning  |Machine Learning Engineer |[akbarsigit](https://github.com/akbarsigit)|
| Muhammad Rifat Bagas Adikusuma | M169DSX0536  |  Machine Learning  | Machine Learning Engineer | [muhammadrifatba](https://github.com/muhammadrifatba) |

## Tech Stack
![TensorFlow](https://img.shields.io/badge/TensorFlow-%23FF6F00.svg?style=for-the-badge&logo=TensorFlow&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white)
![Keras](https://img.shields.io/badge/Keras-%23D00000.svg?style=for-the-badge&logo=Keras&logoColor=white)
![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white)
![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)

## About 
We have 3 model in this repository
### Plant Disease Detection
[Plant disease Detection ](https://github.com/akbarsigit/Pedotan-MachineLearning/blob/main/crop_disease_detection.ipynb) 
(image classification) use InceptionV3 as the base model for transfer learning that taken from [Keras](https://keras.io/api/applications/inceptionv3/). The model also contain additional layer that received ouput from based model. The model had 36 node to define its 36 classification category.  [Plant Disease Classification Merged Dataset](https://www.kaggle.com/datasets/alinedobrovsky/plant-disease-classification-merged-dataset) that contain 18.96 GB images of various plant disease. 

### Nutrient Deficiency Detection
- [Nutrient Deficiency Detection](https://github.com/akbarsigit/Pedotan-MachineLearning/blob/main/leafNutrient.ipynb)
  
### Ideal Farm Detection
- [Ideal Farm Detection](https://github.com/akbarsigit/Pedotan-MachineLearning/blob/main/cropCNN.ipynb)

## Model Performance
Models | Accuracy | Val Accuracy
------------ | ------------- | -------------
Plant Disease Detection | 97.02 % | 96.37 %
Nutrient Deficiency Detection | 99.08% | 94.78%
Ideal Farm Detection | 96.56% | 98.75%


## Run the ipynb in Google Colab
1. Download or clone this repository.
2. Open google colab
3. Import the ,ipynb file
4. Run the code

## Run in Local

1. Download the ipynb file or clone this repostitory
2. Run this locally using ex: jupyter notebook
3. Install all the dependencis
  ```
  ! pip install -r requirements.txt
  ```
4. Run all the code


