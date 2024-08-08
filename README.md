Logistic regression predicts the output of a categorical dependent variable. In Logistic regression, instead of fitting a regression line, we fit an "S" shaped logistic function, which predicts two maximum values (0 or 1). E.g., presence of hypertension, The curve from the logistic function indicates the likelihood of something.

![image](https://github.com/user-attachments/assets/12e44180-916b-4ddb-9a0d-2b86c3dcf84c)

**Assumptions in logistic regression are:**
- The dependent variable must be categorical in nature
- The independent variable should not have multi-collinearity

**Algorithm:**
- Importing libraries
- Pre-processing data
- Selecting Dependent & Independent variables
- Splitting data into train & test set & Importing train test split model
- Calling the Algorithm & building a predictive model
- Prediction
- Generating confusion matrix, accuracy score & evaluating gooodness of fit of the model

**Results:**

Accuracy score of 0.9 was obtained for the predictive model build to predict the malignancy of tumor (benign or malignant) depending upon the radius and texture of tumor.
