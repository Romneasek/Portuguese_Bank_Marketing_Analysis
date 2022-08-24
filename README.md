# Logistic_Regression_Project


Section I : Data Loading<br>
Part I : Load the dataset into the notebook
Part II : Explore and make note of Attribute Information from UCI
Part III : What is the significance of the y column in the dataset and what are the value counts of the y column?
Part IV : What is the ratio of the two classes ? Are they balanced ?<br>
<br>
Section II : Data Cleaning<br>
Since this is real world data , A good practice is to make sure the dataset is devoid of any nuances
<br>
Part I : Get the dtypes of all the columns of our dataset
Part II : Refering to the UCI data description , explore the data in your columns and check if there are any errors
Part III : Make note of the deviation in the dataset compared to the description provided by UCI
Part IV : Using Data Cleaning principles you learned from Pandas Tutorial) figure out the best ways to get rid of the dirty data Part V : Print the cleaned data<br>
<br>
Section III : Exploring data with Group by<br>
In this section , we must create some primitive EDA
<br>
Use the groupby function on the mean of the following columns :
<br>
I : y
II : job
III : marital
IV : education
<br>
Make a note of what you learn from the outputs !<br>
<br>
Section III : Exploratory Data Analysis<br>
Let us put Matplotlib to use !
<br>
Part I : Create bar graphs to the frequency of purchase with respect to the job , martial etc
Part II : Also create stacked bars to same data columns with respect to
Part III : Explore the age column using a histogram and note down your observations<br>
<br>
Section IV : Categorical Variable Encoding<br>
Part I : Create dummy variables for your categorial variables
part II : Explore your new dataset with these new dummy variables !
<br>
Section V : Preliminary Training
Part I : Import your Logisitc Regression libraries
Part II : Split your train and test dataset and train on the data
Part III : Make note of the classification report and other metrics<br>
<br>
Section VI : Let's Improve the performance !<br>
Part 0 : What was your answer to Section - Part IV? Do you think class imbalance affects the model performance? Explore SMOTE implementation
<br>
Part I : Make note of the performance from the last training
Part II : Try implementing SMOTE to balance the two class labels
Part III : Make note of the y label data now , what are the rations now ?<br>
<br>
Section VII : Let us Re-Train!<br>
Part I : Explore what RFE means
Part II : Implement your training process inside the RFE
Part III : What are the best columns that your RFE found? Please make a list of it<br>
<br>
Section VIII : Training time !<br>
Now that you have found the best columns for this problem
<br>
Part I : Now train the model with the new data you have created after the RFE
Part II : Create the prediction system to get the metrics such as accuracy<br>
<br>
Section IX : Additional Metrics<br>
Accuracy is not always the best metric
<br>
Part I : Explore what Confusion Matrix means
Part II : Create the confusion matrix for the predictions and make note of the outputs
Part III : Create a classification report and make note of various outputs<br>
<br>
Section X : What's next?<br>
Part I : Make a note of difference in performance?
Part II : Can you recommend more improvements that could give much better results in all metrics?
