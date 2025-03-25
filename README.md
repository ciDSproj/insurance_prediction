# Health Insurance Costs Prediction


## Overview



## Resources Used
- Python 3.7
- Numpy and Pandas for data manipulation
- Matplotlib and Seaborn for data visualization
- scipy.stats for feature scaling
- sklearn for train_test_split data, and building and evaluating the regression models


## Dataset
The Insurance dataset has 1338 observations and 7 attributes and contains medical personal costs billed by a health insurance company:

- age: Age of primary beneficiary
- sex: Insurance contractor gender, female, male
- bmi: Body Mass Index, providing an understanding of body, weights that are relatively high or low relative to height, objective index of body weight (kg/m^2) using the ratio of height to weight, ideally 18.5 to 24.9
- children: Number of children covered by health insurance / Number of dependents
- smoker: Smoking
- region: The beneficiary's residential area in the US, northeast, southeast, southwest, northwest.
- charges: Individual medical costs billed by health insurance


## Data Visualization
While conducting data visualization I looked for answers to the following questions:

- How smoking affects the relationship between BMI and insurance costs?
- How are the insurance costs influenced by age, gender, and smoking?
- Are the insurance charges influenced by the number of dependents or region?

Below are some of the visualizations I made:







## Data Preprocessing
- Remove duplicates
- Check for missing values
- Detect and remove outliers
- Discretization: bin variables
- Category encoding: one-hot encoding
- Normalize features : min-max normalization
- Split the data into training and testing sets


## Build Regression Models



