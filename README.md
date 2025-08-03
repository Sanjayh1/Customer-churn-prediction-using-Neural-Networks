## Churn Prediction Model
This repository contains a machine learning model to predict customer churn. The project focuses on data analysis, model training, and performance evaluation to provide actionable insights for customer retention strategies.

## Data Science Libraries

- pandas (for data manipulation)

- scikit-learn (for metrics like classification_report)

- keras (for building the deep learning model)

- matplotlib (for plotting visualizations)

## Key Features
- **Data Analysis:** The notebook includes an exploration of customer data, analyzing various factors such as product ownership, age, tenure, and their correlation with churn.

- **Low-Code Model Development:** A deep learning model is built using a low-code approach, with a focus on simplicity and accessibility.

- **Model Performance Evaluation:** The model's performance is evaluated using key metrics like precision, recall, and F1-score. Classification reports and confusion matrices are generated for both training and validation datasets.

- **Visualizations:** The notebook includes visualizations of model performance over epochs, such as loss and accuracy plots, to help understand the training process.

## Methodology and Solutions
The core of the churn prediction solution is a multi-layer neural network, also known as a multi-layer perceptron (MLP). This network is structured to process the tabular customer data and classify customers as either churn or no-churn. The model typically consists of an input layer corresponding to the features of the customer data, one or more hidden layers with activation functions like ReLU to learn complex patterns, and an output layer with a sigmoid activation function to produce a binary classification probability. The use of a deep learning model allows for the discovery of non-linear relationships in the data that traditional models might miss, leading to more accurate predictions.

## Recommendations
Based on the model's analysis and the insights gained from the data, the following recommendations are made to improve customer retention:

- **Product Diversification:** A significant portion of customers own only one product. Incentivize these customers to diversify their product holdings through promotions, bundled services, or special offers.

- **Age-Specific Services:** Since customer churn is positively correlated with age, consider developing services, benefits, or communication strategies tailored to specific age groups to better meet their needs and increase loyalty.

- **Early Tenure Retention:** The highest rates of customer churn occur during the first year of a customer's relationship with the bank. Implement strong onboarding programs, personalized services, or early-bird promotions to build a solid foundation and retain customers during this critical period.

Further Investigation: Conduct a deeper analysis to understand why customers who have purchased more than two products have such a high churn rate. This could be due to specific product combinations, service issues, or other factors that need to be investigated.
