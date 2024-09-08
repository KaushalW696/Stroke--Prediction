  ![istockphoto-1249957366-612x612](https://github.com/Saurabh6912/Stroke_Predictions/assets/135308872/2203d7d9-77fc-45b2-bd80-a84af137c8d6)

# Stroke_Prediction
stroke prediction using Machine learning with visualization using python.

# Live Application
*[https://huggingface.co/spaces/Saurabh0609/BrainStrokePredictor_]*

## Overview
Welcome to the Brain Stroke Prediction project! This repository contains a machine learning model that aims to predict the likelihood of an individual experiencing a brain stroke based on various health and demographic factors. Brain strokes, also known as cerebrovascular accidents (CVAs), are a critical medical condition that requires prompt attention and treatment.

## How Brain Stroke occurs
A brain stroke occurs when there is a sudden interruption of blood supply to the brain, resulting in a lack of oxygen and nutrients to brain cells. This can lead to cell damage or death, causing various neurological complications.

**According to WHO  Stroke is 2nd Leading disease in the world.** So we must need to take seriously this.

# Project Overview
By leveraging the power of machine learning, we have developed a predictive model that analyzes several key features and generates a risk assessment for stroke occurrence.

## Data
The predictive model is trained on a well-curated dataset containing anonymized records of individuals, each represented by a set of attributes, including but not limited to:

* **`gender`**: The gender of the individual (e.g., Male or Female).
* **`age`**: The age of the individual in years.
* **`hypertension`**: Whether the individual has hypertension (0 for No, 1 for Yes).
* **`heart_disease`**: Whether the individual has heart disease (0 for No, 1 for Yes).
* **`ever_married`**: Whether the individual is ever married (Yes or No).
* **`work_type`**: The type of work the individual is engaged in (e.g., Private, Self-employed, Govt_job, etc.).
* **`Residence_type`**: Whether the individual lives in an Urban or Rural area.
* **`avg_glucose_level`**: The average glucose level in the individual's blood.
* **`bmi`**: The body mass index (BMI) of the individual.
* **`smoking_status`**: The smoking status of the individual (e.g., formerly smoked, never smoked, or currently smoking).
* **`stroke`**: The target variable indicating whether the individual experienced a stroke (0 for No, 1 for Yes).

## Model
Our machine learning model is based on a supervised learning algorithm, carefully trained on the labeled dataset. We utilized a EDA with combination of feature engineering, data preprocessing, visualization etc and with use of hyperparameter tuning to optimize the model's performance. As a result, it can accurately classify individuals into two groups: **"at risk of stroke"** and **"not at risk of stroke."**

In a project our predictive model uses Hybrid Algorithm named as Voting Classifier which combines LR, SVM, KNN, RF and ANN algorithms. I have checked the accuracy of all of them. We combined all models to make accurate predictions on purely unseen data & to balance False positive and False Negative cases.

## Usage

* Clone the repository to your local machine.
* Install the required dependencies and libraries specified in the requirements.txt file.
* Prepare your input data with the necessary attributes to predict the stroke risk.
* Utilize the provided functions or pickle file to apply the trained model to your data.
* The model will output of stroke risk.

# Potential Impact

The Brain Stroke Prediction project has the potential to significantly impact healthcare by aiding medical professionals in identifying individuals at high risk of stroke. Early intervention and preventive measures can be taken to reduce the likelihood of stroke occurrence, potentially saving lives and improving the quality of life for patients. It also serves as a stepping stone for further research in the field of medical predictive analytics.

**Please note that the predictions generated by this model are not a substitute for professional medical advice.** It is essential to consult with qualified healthcare providers for accurate assessment and personalized care.

We hope that this project will contribute to the ongoing efforts to enhance stroke prevention and provide valuable insights into the field of medical data analysis.

Thank you for your interest in the Brain Stroke Prediction project.Together, let's make a positive impact on people's lives! 🧠

## Credits
*Image by [iStock by Getty Images](https://www.istockphoto.com/photos/brain-stroke).*

*Contributer [(https://github.com/KaushalW696)*
