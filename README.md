![penguin](https://user-images.githubusercontent.com/100838547/224485944-79342f50-ef8d-40fe-8523-0e903060e0d2.jpg)

# Adelie-and-Chinstrap-Penguins
This project focuses on Adelie and Chinstrap Penguins,as these particular species has been in decline.
In this activity, I will conduct simple linear regression on the penguins dataset (gotten from Seaborn datasets)
## Project Questions:
1. What do you observe about the different aspects of penguins shown in the data
2. What do you observe about the number of rows and columns in the data
3. Drop the rows with missing values
4. Using a scatter plot, check if the linearity assumption is met
5. Check if both flipper length and body mass are normally distributed
6. Check if the assumption of independent observations is met by considering the context of what each entry in the data represents and how it would have been collected
7. Write the linear regression formula for modeling the relationship between body mass and flipper length 
8. Implement the Ordinary Least Square (OLS) approach for linear regression
9. Create a linear regression model for the data, fit the model to the data
10. Get a summary of the results from the model

## Process
### Step 1: Data Preparation
* Import the dataset and the relevant python libraries into the notebook. Carried out data cleaning and exploration by studying the data set and found that there are 4 species of penguins in the data and also checked for missing values. I found that there are 11 rows with missing values and deleted the rows with missing values  since it is not that much considering the total number of rows in the data.
* Another important step in the data cleaning, was to filter the data to include only Adelie and Chinstrap Penguins as these are my focus in this project.

### Step 2: Model
I checked if the model assumptions for linear regression can be made from the data through exploratory data analysis and data visualization, and found that the assumptions are met. That is why I used the linear regression model for this project.

### Step 3: Evaluation
The results of a linear regression model can be used to express the relationship between two variables along with measures of uncertainty.

### Outcomes
There is a notable relationship between flipper length and body mass for Adelie and Chinstrap penguins, with a p-value of 0.000 and standard error of 3.620. For such penguins with 1 millimeter longer flippers, their body mass is 29.4380 grams more on average. If you are looking for insight that will help determine how to distribute food amongst penguins of these species at your zoo, consider the following: You could allocate resources so that penguins with longer flippers are fed larger servings proportional to their flipper length, to support/sustain their body mass.

#### View code: https://github.com/ellaclauz/Adelie-and-Chinstrap-Penguins/blob/main/Adelie_Chinstrap_Penguins.ipynb
