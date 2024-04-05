<!-- hide -->
# Linear regression - Step by step guide
<!-- endhide -->

- Understand a new dataset.
- Process it by applying exploratory data analysis (EDA).
- Model the data using logistic regression.
- Analyze the results and optimize the model if possible.


### Predicting the cost of health insurance for a person

The important insurance company 4Geeks Insurance S.L. wants to calculate, based on physiological data of its customers what will be the premium (cost) to be borne by each of them. To do this, it has assembled a whole team of doctors and based on data from other companies and a particular study have managed to gather a set of data to train a predictive model.

#### Step 1: Loading the dataset

In this dataset you will find the following variables:

1. `age`. Age of primary beneficiary (numeric)
2. `sex`. Gender of the primary beneficiary (categorical)
3. `bmi`. Body mass index (numeric)
4. `children`. Number of children/dependents covered by health insurance (numeric)
5. `smoker`. smoker (categorical)
6. `region`. Beneficiary's residential area in the U.S.: northeast, southeast, southwest, northwest (categorical)
7. `charges`. Health insurance premium (numerical)

#### Step 2: Perform a full EDA

This second step is vital to ensure that we keep the variables that are strictly necessary and eliminate those that are not relevant or do not provide information. Use the example Notebook we worked on and adapt it to this use case.


#### Step 3: Build a linear regression model

You do not need to optimize the hyperparameters. Start by using a default definition and improve it in the next step.

#### Step 4: Optimize the previous model

After training the model, if the results are not satisfactory, optimize it if possible.

> NOTE: Solution: https://github.com/4GeeksAcademy/linear-regression-project-tutorial/blob/main/solution.ipynb
