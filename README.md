# Movies-ETL

## Background
Amazing Prime loves the dataset and wants to keep it updated on a daily basis. Britta needs your help to create an automated pipeline that takes in new data, performs the appropriate transformations, and loads the data into existing tables. You’ll need to refactor the code from this module to create one function that takes in the three files—Wikipedia data, Kaggle metadata, and the MovieLens rating data—and performs the ETL process by adding the data to a PostgreSQL database.

![](Intro.PNG)

## This new assignment consists of four technical analysis deliverables:

### - Deliverable 1: Write an ETL Function to Read Three Data Files
 Using Python, Pandas, the ETL process, and code refactoring, write a function that reads in the three data files and creates three separate DataFrames.
 
![](Resources/1.PNG)


### - Deliverable 2: Extract and Transform the Wikipedia Data
Using Python, Pandas, the ETL process, and code refactoring, extract and transform the Wikipedia data so you can merge it with the Kaggle metadata. While extracting the IMDb IDs using a regular expression string and dropping duplicates, and the use a try-except block to catch errors.

![](Resources/2.PNG)


### - Deliverable 3: Extract and Transform the Kaggle data
Using Python, Pandas, the ETL process, and code refactoring, extract and transform the Kaggle metadata and MovieLens rating data, then convert the transformed data into separate DataFrames. Then merge the Kaggle metadata DataFrame with the Wikipedia movies DataFrame to create the movies_df DataFrame. Finally, merge the MovieLens rating data DataFrame with the movies_df DataFrame to create the movies_with_ratings_df.

![](Resources/3.PNG)


### - Deliverable 4: Create the Movie Database
Use Python, Pandas, the ETL process, code refactoring, and PostgreSQL to add the movies_df DataFrame and MovieLens rating CSV data to a SQL database.

![](Resources/4.PNG)
