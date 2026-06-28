**Phase 1:Data Understanding**

Date: 28th June 2026

**Task Completed**

• Selected the E-commerce sales dataset from Kaggle.

• Created a Google Colab Notebook.

• Imported the dataset using Pandas.

• Performed initial data profiling using:

    • df.head()
  
    • df.info()
  
    • df.dtypes
  
    • df.shape
  
    • df.describe()
  
    • df.isnull().sum()
  
    • df.duplicated().sum()
  
**Findings**

• Dataset contains 5000 rows and 14 columns.

• No missing values were identified.

• No duplicate records were found.

• Generated descriptive statistics for numerical columns.

• Verified the overall sructure of the dataset before beginning data cleaning.


**Key Observations**

The Profit column has:

   • Average Profit: 15,941.75
 
   • Minimum Profit: 19.12
 
   • Maximum Profit: 89,688.44
 

The large variation in profit values suggests that the distribution may contain high-value transactions or outliers. This will be investigated further during the Exploratory Data Analysis (EDA) phase.

**Lessons Learned**

During this phase, I learned how to perform initial data profiling using Pandas. I gained an understanding of the purpose of functions such as head(), info(), shape, dtypes, and describe(), as well as techniques for identifying missing values and duplicate records. This process helped me verify the quality and structure of the dataset before moving to the next stage of the project.

