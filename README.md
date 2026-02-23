# Creating-and-Loading-Datasets
# Experiment 10
## Aditi Rathore
## 25070123006
## EnTC A1
________________________________________
# Aim
## To create a dataset in Python and perform basic data inspection operations such as size, shape, info, and describe using Pandas.
________________________________________
# Objectives
## •	To create a dataset using a dictionary
## •	To convert it into a DataFrame
## •	To upload/read a dataset from a CSV file
## •	To perform basic data analysis using:
### o	shape()
### o	size()
### o	info()
### o	describe()
### o	head() and tail()
________________________________________
# Software Requirement
## •	Python 3.x
## •	Pandas library
## •	Jupyter Notebook / Google Colab / Python IDE
________________________________________ 
# Theory
## A dataset is a collection of related data. In Pandas, datasets are stored in the form of a DataFrame.
## Datasets can be:
### 1.	Created manually
### 2.	Uploaded from external files such as:
#### o	CSV
#### o	Excel
#### o	JSON
#### o	SQL
________________________________________
# Basic Inspection Functions
## Basic inspection functions help to:
### •	Understand the structure of the dataset
### •	Identify missing values
### •	Know data types
### •	Get statistical summary
## Some Examples:
### df.shape	---> Number of rows and columns
### df.size	---> Total number of elements
### df.info()	---> Structure of dataset
### df.describe()	---> Statistical summary
### df.head()	---> First 5 rows
### df.tail()	---> Last 5 rows
### df.columns	---> Display column names
________________________________________
# Program
## Part A: Creating Dataset
### (Done in the code)
________________________________________
## Part B: Basic Dataset Inspection
### (Described in the code)
________________________________________
## Part C: Saving Dataset
### df.to_csv("students.csv", index=False)
________________________________________
## Part D: Uploading / Reading Dataset
### df2 = pd.read_csv("students.csv")
### print("\nUploaded Dataset:\n", df2)
________________________________________
# Output
### •	Dataset created successfully
### •	Shape and size displayed
### •	Column names shown
### •	Dataset structure obtained using info()
### •	Statistical summary generated
### •	CSV file created and uploaded successfully
________________________________________
# Conclusion
### Through this experiment, we have learnt how to create and upload a dataset successfully, and have also performed basic inspection operations such as shape(), size(), info(), and describe() using Pandas.
