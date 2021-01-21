# Pneumonia CNN 
Flatiron Module 3 Project Dipta Roy & Avidan Berman. 

## Project Overview

Pneumonia is an infection that inflames the air sacs in one or both lungs. The air sacs may fill with fluid or pus, causing coughing, fever, chills, and difficulty breathing. A variety of organisms, including bacteria, viruses, and fungi, can cause pneumonia. Pneumonia can range in seriousness from mild to life-threatening. It is most serious for infants and young children, people over the age of 65, and people with health problems or weakened immune systems. The goal of our group is to create a Convolutional Neural Network model that can identify pneumonia in x-rays. While medical doctors can generally identify on an x-ray if a patient has pneumonia, it is a process that takes time. We feel that a model like this could save time for doctors and lead to larger projects where models could identify other diseases in the lungs (ie. COVID-19).

## The Approach
- Download data from Kaggle

- Explore data

- Run baseline model
 
- Fixed class imbalance 

- Adjusted and tuned model for optimal results

- Found outside test data for further testing of the model's capabilities

- Reviewed model results

## The Model
Our team started by creating training, testing, and validations sets. Next, our team tested a baseline CNN model and used both the accuracy and f1 metric to judge the abilities of our model. After reviewing the results of our model we searched for additional x-rays and used data augmentation techniques to solve our class imbalance. Once we solved the issue of class imbalance, we went through the process of tuning our model until we found the best model. The results of our best model were 92% Accuracy and 94% F1-score. After getting our initial results we decided to further test our model on additional data. We are excited to say that our model predicted equally well on the new data.

## Recommendations and Future of the Project
- Based on our findings we have found that it is possible for CNN models to identify Pneumonia in patients.
 
- We recommend that doctors and hospitals move towards machine learning to identifying Pneumonia, this will save all party's time in the long run.
 
- In the future, we would like to expand our model to identifying other respiratory diseases.
 
- Lastly, we would like to create a front end to our model for medical professionals to use when attempting to identify Pneumonia.

## You can read the blog @:
https://roydipta.medium.com/training-a-neural-network-to-identify-pneumonia-in-x-rays-e05a27982443 

 
