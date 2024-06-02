# **Medical-Insurance-Cost-Prediction**
This project aims to calculate medical insurance costs involves using machine learning models to estimate the expenses an individual or group may incur based on various factors such as age, gender, BMI, smoking habits, region, and others.

### **Data Description**

The dataset used in the analysis is called Insurance.csv and it contains the following attributes:

      1. Age: Includes the age of the person applying for insurance.
      
	  2. Sex: The gender of person - Either Male or Female

	  3. BMI: The bmi of the person in numerical format.

	  4. Children: The number of children the person bears.

	  5. Smoker: Is the person a smoker or not.

      6. Region: The area in which the person lives.

      7. Charges: The amount in dollars, charges incurred to the person as medical 
                  expenses.

  ### **Steps Involved**

    1. **Data Preprocessing**:
    	- Load the dataset.
    	- Find inconsistencies and missing values in dataset and eliminate if any.
    	- Convert categorical variables (e.g., gender, smoking status) into 
              numerical representations using techniques like one-hot encoding.

	2. **Exploratory Data Analysis**:
    	- Explore the dataset to gain insights into the relationships between 
              different features and the target variable (medical insurance costs).
    	- Visualize distributions, correlations, and trends in the data to identify 
              patterns and potential predictive factors. 

	3. **Model Selection and Training**:
    	- Split the dataset into training and testing sets to evaluate the 
              performance of the trained models.
            - Create a Regression Model and train it with training data.
    	- Evaluate the performance of the trained model using appropriate metrics 
              such as mean absolute error (MAE), mean squared error (MSE), or R-                squared (R2) score.

	4. **Predictive System**:
    	- By providing the input data on the trained model, the model produces an 
              estimatation of the insurance cost that can be covered.

### **Results**

As a result of analysis conducted the model is a highly accurate model with an R-Square error of 0.74. It provides accurate results estimating medical insurance costs which can be valuable for insurance companies, healthcare providers and individuals seeking to plan their healthcare expenses
