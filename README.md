# LR_Delivery_Time_Prediction
The objective of this assignment is to build a regression model that predicts the delivery time for orders placed through Porter.

![New-Logo-Image-1-1920x1080](https://github.com/user-attachments/assets/95f500ee-b686-4336-bd07-57d93425d16f)

### Project Overview

The objective of this assignment is to build a regression model that predicts the delivery time
for orders placed through Porter. The model will use various features such as the items
ordered, the restaurant location, the order protocol, and the availability of delivery partners.

The key goals are:
- Predict the delivery time for an order based on multiple input features.
- Improve delivery time predictions to optimise operational efficiency.
- Understand the key factors influencing delivery time to enhance the model's accuracy.

### Tasks

- Load the data
- Reading and Understanding the data.
- Fixing the datatype.
- Feature Engineering.
- Creating training and validation sets
- EDA on Training Data.
- Visualising the data.
- Correlation Analysis.
- Handling negative values and outliers.
- EDA on Test Data.
- Model Building.
- Select most important features using RFE method.
- Residual Analysis
- Making Predictions Using the Final Model
- Model Evaluation

### Findings

- Delivery time is mainly depend on below 3 features:
  1. Total Outstanding Orders - More outstanding orders is a sign of a higher workload for delivery person, which will lead to longer wait times before an order is picked up.
  2. Distance - Longer distances naturally result in longer travel times plus traffic for delivery partners.
  3. Total On-Shift Dashers - More available dashers ensure that orders are picked up and delivered faster, reducing wait times which lowers the delivery time.

### Technologies
- **Python** (Pandas, Numpy, Matplotlib, Seaborn, statsmodels.api, SKLearn)
- Data cleaning & Analysis
- Multiple Linear Regression

### Author
 > Tejashri Pilla
 >> **Contact** - tejashrii.joshi@gmail.com
