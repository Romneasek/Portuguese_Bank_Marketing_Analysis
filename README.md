# Portuguese_Bank_Marketing_Analysis


Section I : Data Loading<br>
Part I : Load the dataset into the notebook<br>
Part II : Explore and make note of Attribute Information from UCI<br>
Part III : What is the significance of the y column in the dataset and what are the value counts of the y column?<br>
Part IV : What is the ratio of the two classes ? Are they balanced ?<br>
<br>
Section II : Data Cleaning<br>
Since this is real world data , A good practice is to make sure the dataset is devoid of any nuances<br>
<br>
Part I : Get the dtypes of all the columns of our dataset<br>
Part II : Refering to the UCI data description , explore the data in your columns and check if there are any errors<br>
Part III : Make note of the deviation in the dataset compared to the description provided by UCI<br>
Part IV : Using Data Cleaning principles you learned from Pandas Tutorial) figure out the best ways to get rid of the dirty data Part V : Print the cleaned data<br>
<br>
Section III : Exploring data with Group by<br>
In this section , we must create some primitive EDA<br>
<br>
Use the groupby function on the mean of the following columns :<br>
<br>
I : y<br>
II : job<br>
III : marital<br>
IV : education<br>
<br>
Make a note of what you learn from the outputs !<br>
<br>
Section III : Exploratory Data Analysis<br>
Let us put Matplotlib to use !<br>
<br>
Part I : Create bar graphs to the frequency of purchase with respect to the job , martial etc<br>
Part II : Also create stacked bars to same data columns with respect to<br>
Part III : Explore the age column using a histogram and note down your observations<br>
<br>
Section IV : Categorical Variable Encoding<br>
Part I : Create dummy variables for your categorial variables<br>
part II : Explore your new dataset with these new dummy variables !<br>
<br>
Section V : Preliminary Training<br>
Part I : Import your Logisitc Regression libraries<br>
Part II : Split your train and test dataset and train on the data<br>
Part III : Make note of the classification report and other metrics<br>
<br>
Section VI : Let's Improve the performance !<br>
Part 0 : What was your answer to Section - Part IV? Do you think class imbalance affects the model performance? Explore SMOTE implementation<br>
<br>
Part I : Make note of the performance from the last training<br>
Part II : Try implementing SMOTE to balance the two class labels<br>
Part III : Make note of the y label data now , what are the rations now ?<br><br>
<br>
Section VII : Let us Re-Train!<br>
Part I : Explore what RFE means<br>
Part II : Implement your training process inside the RFE<br>
Part III : What are the best columns that your RFE found? Please make a list of it<br>
<br>
Section VIII : Training time !<br>
Now that you have found the best columns for this problem<br>
<br>
Part I : Now train the model with the new data you have created after the RFE<br>
Part II : Create the prediction system to get the metrics such as accuracy<br>
<br>
Section IX : Additional Metrics<br>
Accuracy is not always the best metric<br>
<br>
Part I : Explore what Confusion Matrix means<br>
Part II : Create the confusion matrix for the predictions and make note of the outputs<br>
Part III : Create a classification report and make note of various outputs<br>
<br>
Section X : What's next?<br>
Part I : Make a note of difference in performance?<br>
Part II : Can you recommend more improvements that could give much better results in all metrics?<br>
