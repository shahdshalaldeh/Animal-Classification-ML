# Animal-Classification-ML
Animal classification using machine learning and a Random Forest model.

# Animal Classification using Machine Learning

## About the Project

This project uses machine learning to predict an animal's class based on its physical and behavioral characteristics.

The project was created as a simple machine learning classification project using the Zoo dataset.

## Dataset

The dataset contains 101 animals and 16 features describing their characteristics, such as:

- Hair
- Feathers
- Eggs
- Milk
- Airborne
- Aquatic
- Predator
- Toothed
- Backbone
- Breathes
- Venomous
- Fins
- Legs
- Tail
- Domestic
- Catsize

The target variable is `type`, which represents the animal's class.

## Machine Learning Model

A **Random Forest Classifier** was used to train the model.

The dataset was divided into:

- 80% training data
- 20% testing data

The model was trained using the training data and then evaluated on animals it had not seen during training.

## Results

The model achieved an accuracy of **95.24%**.

The model correctly classified **20 out of 21** animals in the test set.

## Tools & Technologies

- Python
- Pandas
- Scikit-learn
- Jupyter Notebook
- Random Forest Classifier

## What I Learned

Through this project, I practiced:

- Preparing a dataset for machine learning
- Separating features (`X`) and target (`y`)
- Splitting data into training and testing sets
- Training a classification model
- Making predictions
- Evaluating a model using accuracy
├── animal_classification_ml.ipynb
└── README.md

## Project Structure

```text
Animal-Classification-ML/
│
├── animal_classification_ml.ipynb
└── README.md


