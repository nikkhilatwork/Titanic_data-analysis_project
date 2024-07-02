# Titanic_data-analysis_project
#Importing the required libraries
#reading & observing data 
#we can read csv file using df = pd.read_csv
#df
#df.head() => shows 1st 5 values  of dataset.
#df.tail() => shows last 5 values of data set.
#by default read function will show data as 1st 5 and last 5 values if data s-ze is large
#df.info() => will display all data sets data type, no of rows and cols, amdn the amount of memory used in data frame
#Data cleaning => Is the process of Identifying and removing incorrect,  duplicate / errors and inconsistent data from data set. making data in standardizing format & correct my data values which is out of range.
#Importance of data cleaning => 
      a) Accurate data is essential for making informed decisions.
      b) data cleaning can help  identify and prevent errors 
      c)data cleaning improves quality of data by removing duplicates, errors
      d)it will improve efficiency of data

#Handeling missing/null values => we will removing the null values (NaN) from data.
#Removing redundency/ Duplicate data => we are checking how many duplicate entries  we have in data and we are going to delete duplicate values.
#Exporting data =>
       then export the data to new cleaned csv file using  ('cleaned_titanic.csv', index=False) 
       index = False state that not to include pandas in it.

#sns.Countplot(data=df, x = ' ', hue = ) => for visualization of data. 
#sns.pairplot(data = df) => show relationship between each  pair of variable in data. 
#df.corr() => used for  correlation between data.

      

