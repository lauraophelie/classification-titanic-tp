# Titanic Classification

This project is a simple machine learning exercise using classification. The goals are to build, visualize, evaluate and compare a Decision Tree and a Random Forest from a dataset about the Titanic.

# Dataset 

The original dataset is named **Titanic – Machine Learning from Disaster** and can be retrieved here : https://www.kaggle.com/c/titanic/data

# Technologies used

- Programming Language used : Python
- Libraries used : pandas, numpy, seaborn, matplotlib, scikit-learn
- App / tool used : Jupyter Notebook

# Process

This exercise was done in multiple parts :

**1. Loading and Exploration :**
- Loading the titanic dataset - using pandas to load the csv file and display the data in the form of a dataframe
- Doing simple exercises such as displaying the total amount of passengers, survivors and calculating the proportions 
- Identifying the columns with missing values : `Age`, `Cabin`, `Embarked`

**2. Cleaning and Preparation**
- Inputing the missing values : 
    - replacing the value of `Age` by the **median** : 28.0
    - replacing the value of `Embarked` by the most frequent modality : S
- Deleting useless columns such as : `PassengerId`, `Name`, `Ticket`, `Cabin` as they do not bring any real / concrete value. 
- Creating a new variable called `Title` based on `Name` and visualizing its distribution : this new variable can help improving the survival prediction because it indicates the genre, the social class and sometimes the age of the passenger 

**3. Encoding and Pre-treatment**

**4. Visualisation and Exploratory analysis**

**5. Decision Tree**

**6. Random Forest**

**7. Analysis and Optimisation**

**8. Conclusion**