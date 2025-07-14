# 🚗 Car Evaluation Using Decision Trees

## Overview
This project applies **Decision Tree algorithms** to predict the acceptability of cars based on various categorical attributes such as buying price, maintenance cost, number of doors, passenger capacity, luggage boot size, and safety level. The dataset originates from the UCI Machine Learning Repository and is derived from a hierarchical decision model developed for DEX demonstration purposes.

## Dataset
The Car Evaluation dataset maps car acceptability to six input features:

- **Buying:** vhigh, high, med, low  
- **Maintenance:** vhigh, high, med, low  
- **Doors:** 2, 3, 4, 5more  
- **Persons:** 2, 4, more  
- **Lug_boot:** small, med, big  
- **Safety:** low, med, high  

**Target classes (car acceptability):**  
- unacc (unacceptable)  
- acc (acceptable)  
- good  
- vgood (very good)  

## Methodology
Decision Tree models using both **Gini impurity** and **Entropy** criteria are implemented with Python’s Scikit-learn library. The workflow includes data preprocessing (label encoding), model training, evaluation using accuracy and confusion matrix, and visualization of the decision tree.

## Results
The decision tree classifier achieved approximately **78% accuracy** in predicting car acceptability on the test set.

## Usage
To run this project locally:

```bash
git clone https://github.com/your-username/car-evaluation-decision-tree.git
cd car-evaluation-decision-tree
pip install -r requirements.txt
jupyter notebook notebooks/car_evaluation_decision_tree.ipynb
