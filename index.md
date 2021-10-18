# Data Science Portfolio

Here are some of my best Data Science Projects. I have explored various machine-learning algorithms for different datasets. Feel free to contanct me to learn more about my experience working with these projects.

***

[Examining the effect of environmental factors and weather on Bike rentals](https://github.com/mohantechis/Seoul_Bike_dataSet.git)

<img src="images/seoul-bikes.jpeg?raw=true"/>

- Used Linear Regression to predict the number of bikes rented in the city of Seoul
- The data had quite a few categorical variables which were encoded for use in the model
- Encoded categorical variables to numeric using Sklearn due to the presence of many string columns
- Fit a multiple linear regression model with high prediction accuracy through iteration

***

[Portuguese banking institution.
The classification goal is to predict if the client will subscribe a term deposit (variable y).
](https://github.com/mohantechis/Banking_Institution_Project.git)

<img src="images/bank1.png?raw=true"/>

- Since this is real world data , A good practice is to make sure the dataset is devoid of any nuances

1. Get the dtypes of all the columns of our dataset 
2. Refering to the UCI data description , explore the data in your columns and check if there are any errors 
3. Make note of the deviation in the dataset compared to the description provided by UCI 
4. Using Data Cleaning principles you learned from Pandas Tutorial) figure out the best ways to get rid of the dirty data 
5. Print the cleaned data Used Logistic regression classifier & optimized the accuracy by using the ROC curve
6. Use the groupby function on the mean of the following columns :

I : y II : job III : marital IV : education

Make a note of what you learn from the outputs !
# EDA Part
Part 1 : Create bar graphs to the frequency of purchase with respect to the job , martial etc 
Part II : Also create stacked bars to same data columns with respect to job
Part III : Explore the age column using a histogram and note down your observations

***

[Identifying symptoms of orthopedic patients as normal or abnormal](https://github.com/mohantechis/KNN_NB_Project.git)

<img src="images/knee-brace-ortho.png?raw=true"/>

- Used the K Nearest Neighbours algorithm to classify a patient's condition as normal or abnormal based on various orthopedic parameters
- Compared predictive performance by fitting a Naive Bayes model to the data
- Selected best model based on train and test performance
