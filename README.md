# Breast-Cancer-Predictor
A machine learning based system that can be used to predict the possibility of the presence of the breast cancer in a person.
## Table of Contents
[Introduction](#Introduction)
[Requirements](#Requirements)
[How-To-Use](#How-To-Use)
[Dataset](#Dataset)
[Technical-Details](#Technical-Details)
[Algorithm](#Algorithm)
[Lisence](#Lisence)
### Introduction
Breast Cancer is one of the most prevalent disease now a days. After skin cancer, breast cancer is the most common cancer diagnosed in women in the United States. Breast cancer can occur in both men and women, but it's far more common in women. Now the diagnosis of this cancer is very costly process and requires a lot of expertize. The conclusiion of whether the person has cancer or not mainly depends on the domain knowledge of the expert. Moreover this is tedious process also. So the objective of this project is to design a machine learning based system that can conclude whether the person has breast cancer or not based on the test reports.
### Requirements
Python 3.5 or above version with numpy,pandas,matplotlib,scikit-learn and pickle packages.
Jupyter lab/Jupyter notebook
No specific hardware requirements and runs on any operating system
### How-To-Use
After downloading and extracting the repository open it in jupyter notebook.Then open the `breastcancer_predictor.ipynb` file. In that file change the values of `report` variable.
The order of the values are `'mean radius', 'mean texture', 'mean perimeter', 'mean area','mean smoothness', 'mean compactness', 'mean concavity','mean concave points', 'mean symmetry', 'mean fractal dimension','radius error', 'texture error', 'perimeter error', 'area error','smoothness error', 'compactness error', 'concavity error','concave points error', 'symmetry error','fractal dimension error', 'worst radius', 'worst texture','worst perimeter', 'worst area', 'worst smoothness','worst compactness', 'worst concavity', 'worst concave points','worst symmetry', 'worst fractal dimension'` and then run all the cells.The presence of breast cancer is displayed as the output of the last cell.

### Dataset
The dataset used in this project is wine dataset from scikit learn dataset library.
It can be loaded as `sklearn.datasets.load_wine()`
### Technical-Details
##### Dataset Details
The dataset contains 30 attributes and 578 instances.
The column details are
mean radius
mean texture
mean perimeter
mean area
mean smoothness
mean compactness
mean concavity
mean concave points
mean symmetry
mean fractal dimension
radius error
texture error
perimeter error
area error
smoothness error
compactness error
concavity error
concave points error
symmetry error
fractal dimension error
worst radius
worst texture
worst perimeter
worst area
worst smoothness
worst compactness
worst concavity
worst concave points
worst symmetry
worst fractal dimension
##### Files Organization
The project is implemented in python in Jupyter Notebook environment.It mainly contains two parts.The `breastcancer_trainer.ipynb` is for training the data and the `breastcancer_predictor.ipynb` is to load the trained data and to predict results.The `breastcancer_model.sav` is the model that is saved.
### Algorithm
The Wine-Classifier is a classification problem.As here there are two types of target values (benign and malignant) this comes under `binomial classification`.
The algorithm used in this is `Support Vector Machines`.More details about this algorithm can be found at <https://en.wikipedia.org/wiki/Support-vector_machine>
### Lisence
This is a public repository and you can be used in research,commercial and non-commercial applications without any restrictions.
