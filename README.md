# Task-1-Data-Cleaning-Preprocessing


# STEP 1 - Importing the dataset  and exploring basic info 

# Imported the .csv file using pandas function pd.read_csv
# Used basic commands to explore info like .describe(), .info(), .dtypes
# To check for null values i used the .isnull().sum() function

# STEP 2 - Handle missing values using mean/median/imputation

# Age,Cabin and Embarked columns had missing values so I used median for age, custom value for Cabin and mode for Embarked

# STEP 3 - Convert categorical features into numerical using encoding

# I found out that name,sex,ticket,cabin,embarked are categorical value
# I dropped the name,ticket,cabin because they were not needed
# Used one hot encoding for sex and embarked to convert them into numerical true and false values

# STEP 4 - Normalize/standardize the numerical features

# Used standardization from the StandardScaler library from sklearn

# STEP 5 - Visualize outliers using boxplots and remove them

# I used seaborn library along with matplotlib for boxplot visualization
# Filtered and removed outliers using IQR

# Kept all the processes pretty clean and simple