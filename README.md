# Data-interview-questions

Questions
If you’re currently employed, why you don’t you like your current job? If you’re not, what are some of the ideal aspects you’re looking for in a data science or data analyst job? What specifically excites you and why do you want to do it?
Out of all of your data analyst projects what was the one you're most proud of and why?
Have you ever found an analysis that was the opposite of what you were hoping for? If not, suppose you performed an analysis where a client was hoping for one outcome, but in fact you got the opposite of what they were hoping it would show? How did you or would you handle this?
You're a consultant. Briefly and concisely describe your approach/process to how you would go about solving this problem: You're given a large corpus of Twitter data. Please predict whether the tweet is a disaster or not.
Explain structured vs unstructured vs semi-structured data.
What are the advantages of RELU?
Explain Loss function vs Cost function vs Objective function.
What is the purpose of the activation function? What happens if I don't use one?
What are hyper-parameters? Can you list some?
L1 vs L2 regularization?
Normalizing vs standardizing inputs? Why do we even do this?
Your model is producing weird results. What is your process of debugging the model?
What id the difference bwteen Mini batch gradient descent vs stochastic gradient descent?
Briefly describe gradient descent with momentum, RMSprop,and Adam.
What are the benefits of Batch Normalization?
You're the new and ONLY DS hire for a company that analyzes medical images. The company has 10 million samples. Of the 10 million samples: 3 million are bone fractures for the foot, 2 million are bone fractures for the knee, and 5 million are bone fractures for the shoulder. The company wants to predict the severity of bone fractures in the foot. How would you split your dataset for train, validation, and testing (what % of each)?
Both in technical and non-technical language, explain Support Vector Machines.
Both in technical and non-technical language, explain the Perceptron.
Both in technical and non-technical language, explain KNNs.
Both in technical and non-technical language, explain K-Means Clustering.
How does K-Means work?
Both in technical and non-technical language (or, to a 5 year old), explain standard deviation.
Both in technical and non-technical language, explain Decision Trees.
Both in technical and non-technical language, explain Naive Bayes.
Both in technical and non-technical language, explain Linear Regression.
Both in technical and non-technical language, explain Logistic Regression.
How do you train Logistic Regression?
Both in technical and non-technical language, explain Perceptron.
Both in technical and non-technical language, explain Bagging.
Both in technical and non-technical language, explain Boosting.
Both in technical and non-technical language, explain LSTMs.
Both in technical and non-technical language, explain CNNs and its architecture.
Both in technical and non-technical language, explain Transformers and Attention.
Both in technical and non-technical language, explain PCA.
Both in technical and non-technical language, explain SVD.
Why do we max pool and what are its benefits?
What are the benefits of padding?
How does ResNet work?
Walk me through how object detection and localization works.
How does a BiLSTM work and what are its advantages?
How does Name Entity Recognition work?
Walk me through an A/B Test. How long do I run it and how do I determine how many samples I need?
Sensitivity vs Specificity vs Recall vs Precision.
Both in technical and non-technical language, explain ROC and AUC.
Stratified vs Cluster sampling.
Both in technical and non-technical language, explain eigenvectors and eigenvalues.
How do I choose the optimal hyper-parameter in K-Means?
What are tensors?
What are the assumptions when using linear regression?
Bayesian Estimate vs Maximum Likelihood Estimation?
What is multicollinearity? Why might it be problematic?
What is R-Square? Write out the formula.
Covariance vs Correlation?
What is a confounding variable?
Explain confidence intervals.
What is TF-IDF?
Discriminative models vs Generative models?
What it an N-gram model?
Stemming vs Lemmatization.
What is word2vec? Explain skip gram. Explain CBOW.
Binomial vs Geometric vs Hypergeometric vs Poisson distributions.
Explain P-values.
Give me a simple example using a t-Test for one mean.
Give me a simple example using confidence intervals.
What is the relationship between Normal distribution and Binomial distribution.
PMF vs PDF vs CDF.
Central Limit Theorem vs Law of Large Numbers.
Permutation vs Combination. Write out both formulas.
Parametric vs Non-Parametric.
Explain Chi-square test.
Why do we divide sample variance by n-1?
How would you determine if males and females have different height

**Question 3 - Given the table users:**
Table "users"        
Column	Type
id	integer
username	character
email	character
city	character
state	character
zip	integer
active	boolean
construct a query to find the top 5 states with the highest number of active users. Include the number for each state in the query result. 
Example result:

state	num_active_users
New Mexico	502
Alabama	495
California	300
Maine	201
Texas	189
The following SQL command will do the intended:

**Question 5 - What are underfitting and overfitting
**in the context of Machine Learning? How might you balance them?

select state, count(id) as num_active_users from users
where active = 1
group by state
order by num_active_users desc
limit 5


Overfitting happens when a model learns the detail and noise in the training data to the extent that it negatively impacts the performance of the model on new data. This means that the noise or random fluctuations in the training data is picked up and learned as concepts by the model. Underfitting refers to a model that can neither model the training data nor generalize to new data. An underfit machine learning model is not a suitable model and will be obvious as it will have poor performance on the training data. Ideally we will want a sweet spot between underfitting and overfitting. So you want the machine to learn the traning set rather well, but not too much that it will not be able to adapt to new sets positevely.


Company: Google

Role: Data Scientist

 

Why do you use feature selection?
What is the effect on the coefficients of logistic regression if two 3. predictors are highly correlated?
What are the confidence intervals of the coefficients?
What’s the difference between Gaussian Mixture Model and K-Means?
How do you pick k for K-Means?
How do you know when Gaussian Mixture Model is applicable?
Assuming a clustering model’s labels are known, how do you evaluate the performance of the model?



Company: Uber

Role: Data Scientist

 

Pick any product or app that you really like and describe how you would improve it.
How would you find an anomaly in a distribution ?
How would you go about investigating if a certain trend in a distribution is due to an anomaly?
How would you estimate the impact Uber has on traffic and driving conditions?
What metrics would you consider using to track if Uber’s paid advertising strategy to acquire new customers actually works? How would you then approach figuring out an ideal customer acquisition cost?
 

Company: TCS

Role: Data Scientist

 

Explain about Time series models you have used?
SQL Questions - Group by Top 2 Salaries for Employees - use Row num and Partition
Pandas find Numeric and Categorical Columns. For Numeric columns in Data frame, find the mean of the entire column and add that mean value to each row of those numeric columns.
What is Gradient Descent? What is Learning Rate and Why we need to reduce or increase? Why Global minimum is reached and Why it doesn’t improve when increasing the LR after that point?
What is Log-Loss and ROC-AUC?
What is Multi-collinearity? How will you choose one features if there are 2 highly correlated features? Give Examples with the techniques used.
VIF – Variance Inflation Factor – Explain.
Do you know to use Amazon SageMaker for MLOPS?
Explain your Projects end to end (15-20mins).
 

Company: Capital One

Role: Data Scientist

 

How would you build a model to predict credit card fraud?
How do you handle missing or bad data?
How would you derive new features from features that already exist?
If you’re attempting to predict a customer’s gender, and you only have 100 data points, what problems could arise?
Suppose you were given two years of transaction history. What features would you use to predict credit risk?
Design an AI program for Tic-tac-toe
Explain overfitting and what steps you can take to prevent it.
Why does SVM need to maximize the margin between support vectors? 



Company: Latentview Analytics

Role: Data Scientist

Experience: 2 years

 

What is mean and median
Difference between normal and gaussian
distribution

What is central limit theorem
What is null hypothesis
What is confidence interval
What is covariance and correlation and how will u
interpret it.

How will you find out the outliers in the dataset
and is it always to remove outliers

Explain about Machine Learning
Explain the algorithm of your choice
Different methods of missing values imputation
Explain me your ml project
How did you handle imbalance dataset
What is stratified samplings
Difference between standard scalar and normal
scalar

Company: Verizon

Role: Data Scientist

 

    How many cars are there in Chennai? How do u structurally approach coming up with that number?
    Multiple Linear Regression?
    OLS vs MLE?
    R2 vs Adjusted R2? During Model Development which one do we consider?
    Lift chart, drift chart
    Sigmoid Function in Logistic regression
    ROC what is it? AUC and Differentiation?
    Linear Regression from Multiple Linear Regression
    P-Value what is it and its significance? What does P in P-Value stand for? What is Hypothesis Testing? Null hypothesis vs Alternate Hypothesis?
Bias Variance Trade off?
Over fitting vs Underfitting in Machine learning?
Estimation of Multiple Linear Regression
Forecasting vs Prediction difference? Regression vs Time Series?
p,d,q values in ARIMA models



Company: Fractal

Role: Data Scientist

 

1.Difference between array and list

2.Map function

Scenario,
if coupon distributed randomly to customers of swiggy, how to check there buying behavior.

Use segmenting customers

Compare customers who got coupon and who did not

Which is faster dictionary or list for look up
How to merge two arrays
How much time svm takes to complete if 1 iteration takes 10sec for 1st class.
And there are 4 classes.

Kernals in svm, there difference




Company name: Infosys

Role: Data scientist

 

1) curse of dimensionality? How would you handle it?

2) How to find the multi collinearity in the data set

3)Explain the difference ways to treat multi collinearity!

4) How you decide which feature to keep and which feature to eliminate after performing multi collinearity test?

5)Explain logistic regression

6)we have sigmoid function which gives us the probabilty between 0-1 then what is the need of logloss in logistic regression?

7) P value and its significance in statistical testing?

8) How do you split the time series data and evaluation metrics for time series data

9) How did you deploy your model in production? How often do you retrain it?




Company: Wipro

Role: Data Scientist

 

Difference between WHERE and HAVING in SQL
Basics of Logistics Regression
How do you treat outliers ?
Explain confusion matrix ?
Explain PCA (Wanted me to explain the co-variance matrix and eigen vectors and values and the mathematical expression and mathematical derivation for co-variance matrix)
How do you cut a cake into 8 equal parts using only 3 straight cuts ?
Explain kmeans clustering
How is KNN different from k-means clustering?
What would be your strategy to handle a situation indicating an imbalanced dataset?
Stock market prediction: You would like to predict whether or not a certain company will declare bankruptcy within the next 7 days (by training on data of similar companies that had previously been at risk of bankruptcy). Would you treat this as a classification or a regression problem?



Company: Accenture

Role: Data Scientist

 

What is difference between K-NN and K-Means clustering?
How to handle missing data? What imputation techniques can be used?
Explain topic modelling in NLP and various methods in performing topic modeling.
Explain how you would find and tackle an outlier in the dataset.
Follow up: What about inlier?
Explain back propagation in few words and its variants?
Is interpretability important for machine learning model? If so, ways to achieve interpretability for a machine learning models?
Is interpretability important for machine learning model? If so, ways to achieve interpretability for a machine learning models?
How would you design a data science pipeline?
Explain bias - variance trade off. How does this affect the model?
What does a statistical test do?
How to determine if a coin is biased? Hint: Hypothesis testing 




Company: Tiger Analytics

Role: Senior Analyst

 

What is deep learning, and how does it contrast with other machine learning algorithms?
2.When should you use classification over regression?

3.Using Python how do you find Rank, linear and tensor equations for an given array of elements? Explain your approach.

4.What exactly do you know about Bias-Variance decomposition? 5.What is the best recommendation technique you have learnt and what type of recommendation technique helps to predict ratings? 6.How can you assess a good logistic model?

7.How to you read the text from an image? Explain?

8.What are all the options to convert speech to text? Explain and name few available tools to implement the same?





My checklist before going for an SQL round of interview:

 

WHERE , AND, OR, NOT, IN
ORDER BY, ASC, DESC
IS NULL
LIMIT
MIN, MAX, COUNT, AVG, SUM
LIKE, WILDCARDS
IN BETWEEN
INNER JOIN
LEFT JOIN
Subqueries(most important)
UNION
GROUP BY
HAVING
LEFT, RIGHT, MID, CONCAT
PARTITION BY, OVER
LEAD,LAG
RANK, DENSE_RANK, PERCENT_RANK
ROW_NUMBER, CUME_DIST
FIRST_VALUE, LAST_VALUE
AS



Company Name : Tata IQ

Role: Data Analyst

 

Why data science as a career?

Stats:

What is p value?

What is histograms?

What is confidence interval?

You are a Sr data analyst at a new Online Cab booking Startups

How you will do data collection and how you will leverage the data to give useful insights to the Company?

Guestimate: No Of cabs booking per day in Ranchi

You are product head manager(not remember exactly) at a NBFC which gives a Secured loans what factors will you consider giving loan to ?

Inventory Database based on that have to do basic pandas/sql query? Joins / merge to get avg sales, its chart?

You have a list of 3 numbers return the min diff. Can use any python/sql

What is Big Data?




Role: Junior Data Scientist

 

1) Explain the architecture of CNN

2)If we put a 3×3 filter over 6×6 image what will be the size of the output image

3) What will you do to reduce overfitting In deep learning models

3) Can you write a program for inverted star program in python

4)Write a program to create a dataframe and remove elements from it

5) I have 2 guns with 6 holes in each, and I load a single bullet In each gun, what is the probability that if I fire the guns simultaneously atleast 1 gun will fire (atleast means one or more than one)

5) There are 2 groups g1 and g2, g1 will ask g2 members to give them 1 member so thay they both will be equal in number, g2 will ask g1 members to give them 1 member so thay they will be double of g1, how many members are there in the groups (I'm not sure of this question as I tried to solve but didnt get correct answer)




Some Data Science Companies(not ranked) for Job Hunting:

 

Genpact
Tredence Analytics
Fractal Analytics
Tiger Analytics
Bridgei2i
Ugam
Latent View
Brillio
Abzooba
AbsolutData
Gramemer
BluePi
Knowledge Foundry
Wipro
TCS
Accenture
Purplle
AbsoluteData
Hansa CEquity
Lymbyc
IBM
PwC
EY
KPMG
Sibia
ZS
ZF
TechVantage
L&T Infotech
Cognizant
Amazon
Microsoft
Walmart
Philips
Ford
JP Morgan
Deloitte
Shell
Mu Sigma
Postman
Altrix
HP
HCL
Dell
Paypal
Fidelity Investments
Rakuten
Infosys
Flipkart
Myntra



Company: Mindtree

Role: Data Scientist

 

What is central tendency
Which central tendency method is used If there exists any outliers
Central limit theorem
Chi-Square test
A/B testing
Difference between Z and t distribution (Linked to A/B testing)
Outlier treatment method
ANOVA test
Cross validation
How will you work in a machine learning project if there is a huge imbalance in the data
Formula of sigmoid function
Can we use sigmoid function in case of multiple classification
What is Area under the curve
Which metric is used to split a node in Decision Tree
What is ensemble learning
3 situation based questions



Company: Genpact

Role: Data Scientist

 

Why do we select validation data other than test data?
Difference between linear logistic regression?
Why do we take such a complex cost function for logistic?
Difference between random forest and decision tree?
How would you decide when to stop splitting the tree?
Measures of central tendency
What is the requirement of k means algorithm
Which clustering technique uses combining of clusters
Which is the oldest probability distribution
What all values does a random variable can take
Types of random variables
Normality of residuals




Company: Ford

Role: Data Scientist

 

How would you check if the model is suffering from multi Collinearity?
What is transfer learning? Steps you would take to perform transfer learning.
Why is CNN architecture suitable for image classification? Not an RNN?
What are the approaches for solving class imbalance problem?
When sampling what types of biases can be inflected? How to control the biases?
Explain concepts of epoch, batch, iteration in machine learning.
What type of performance metrics would you choose to evaluate the different classification models and why?
What are some of the types of activation functions and specifically when to use them? 
What are the conditions that should be satisfied for a time series to be stationary?
What is the difference between Batch and Stochastic Gradient Descent?
What is difference between K-NN and K-Means clustering?



Company: Quantiphi

Role: Machine Learning Engineer

 

What happens when neural nets are too small? What happens when they are large enough?
Why do we need pooling layer in CNN? Common pooling methods?
Are ensemble models better than individual models? Why/why - not?
Use Case - Consider you are working for pen manufacturing company. How would you help sales team with leads using Data analysis?
Assume you were given access to a website google analytics data.
In order to increase conversions, how do you perform A/B testing to identify best page design.
How is random forest different from Gradient boosting algorithm, given both are tree-based algorithm?
Describe steps involved in creating a neural network?
In brief, how would you perform the task of sentiment analysis? 



Company: TheMathCompany

Role: Analyst (Data Science)

 

Central limit theorem
Hypotheses testing
P value
T-test
Assumptions of linear regression.
Correlation and covariance.
How to identify & treat outliers and missing values.
Explain Box and whisker plot.
Explain any unsupervised learning algorithm.
Explain Random forest.
Business and technical questions related to your project.
Explain any scope of improvement in your project.
Questions based on case studies.
Write SQL query to find employee with highest salary in each department.
Write SQL query to find unique email domain name & their respective count
Solve question (17) using Python.
 

Rounds:

Technical Test (Python, SQL, Statistics) (Coding+MCQ) (90 min).
Telephonic interview (10 min).
Technical interview (45 min).
Fitment interview (25 min).
HR interview (30 min).




Company: Cognizant

Role: Data Scientist

 

SQL question on inner join and cross join
SQL question on group-by
Case study question on customer optimization of records for different marketing promotional offers
Tuple and list
Linear regression
Logistic regression steps and process
Tell me about your passion for data science? Or What brought you to this field?
What is the most common problems you face whilst working on data science projects?
Describe the steps to take to forecast quarterly sales trends. What specific models are most appropriate in this case?
What is the difference between gradient and slope, differentiation and integration?
When to use deep learning instead of machine learning. Advantages, Disadvantages of using deep learning?
What are vanishing and exploding gradients in neural networks?



Company: Husqvarna Group

Role: Data Scientist

 

Telecom Customer Churn Prediction. Explain the project end to end?
Data Pre-Processing Steps used.
Sales forecasting how is it done using Statistical vs DL models - Efficiency.
Logistic Regression - How much percent of Customer has churned and how much have not churned? 
What are the Evaluation Metric parameters for testing Logistic Regression? 
What packages in Python can be used for ML? Why do we prefer one over another?
Numpy vs Pandas basic difference.
Feature on which this Imputation was done, and which method did we use there?
Tuple vs Dictionary. Where do we use them?
What is NER - Named Entity Recognition?




Company: Deloitte

Role: Data Scientist

 

Conditional Probability
Can Linear Regression be used for Classification? If Yes, why if No why?
Hypothesis Testing. Null and Alternate hypothesis
Derivation of Formula for Linear and logistic Regression
Why use Decision Trees?
PCA Advantages and Disadvantages?
What is Naive Bayes Theorem? Multinomial, Bernoulli, Gaussian Naive Bayes.
Central Limit Theorem? 
Scenario based question on when to use which ML model?
Over Sampling and Under Sampling
Over Fitting and Under Fitting
Core Concepts behind Each ML model mentioned in my Resume.
Genie Index Vs Entropy
how to deal with imbalance data in classification modelling?



Company: Wipro

Role: Data Scientist

 

What is a Python Package, and Have you created your own Python Package?
Explain about Time series models you have used?
SQL Questions - Group by Top 2 Salaries for Employees - use Row num and Partition
Pandas find Numeric and Categorical Columns. For Numeric columns in Data frame, find the mean of the entire column and add that mean value to each row of those numeric columns.
What is Gradient Descent? What is Learning Rate and Why we need to reduce or increase? Why Global minimum is reached and Why it doesn’t improve when increasing the LR after that point?
Two Logistic Regression Models - Which one will you choose - One is trained on 70% and other on 80% data. Accuracy is almost same.
What is Log-Loss and ROC-AUC?
Do you know to use Amazon SageMaker for MLOPS?
Explain your Projects end to end (15-20mins).




Company: Infosys

Role: Data Scientist

 

1) Measures of central tendency

2) What is the requirement of k means algorithm

3) Which clustering technique uses combining of clusters

4) Which is the oldest probability distribution

5) What all values does a random variable can take

6) Types of random variables

7) Normality of residuals

8) Probability questions

9) Sensitivity and specificity etc.

10) Explain bias - variance trade off. How does this affect the model? 

11) What is multi collinearity? How to identify and remove it.




Company: Tiger Analytics

Role: Data Scientist

 

What are the projects done by you.
Suppose there is a client who wants to know if giving discounts is beneficial or not. How would you approach this problem?
The same client want to know how much discount he should give in the next month for maximum profits.
Can you have a modeling approach to say in last year what mistakes client did in giving discounts. Meaning if they should have have a different discount and increased sales.
What feature engineering techniques you used in past projects.
What models you used and selected the final model.



Company: Genpact

Role: Data Scientist

 

What makes you feel that you would be suitable for this role, since you come from a different background?
What is an imbalanced data set??
What are the factors you will consider in order to predict the population of a city in the future?
Basic statistics questions?
What are the approaches for treating the missing values?
Evaluation metrics for Classification?
Bagging vs Boosting with examples
Handling of imbalanced datasets
What are your career aspirations?
10.What's the graph of y = |x|-2

esstimate on no. Of petrol cars in Delhi
12.Case study on opening a retail store

13.Order of execution of SQL





Company: Ericsson

Role: Data Scientist

 

Round No: 1st Round

 

How to reverse a linked list

 

Give a logistic regression model in production, how would you find out the coefficients of different input features.

 

What is the p- value in OLS regression

 

What's the reason for high bias or variance

 

Which models are generally high biased or high variance

 

Write code to find the 8 highest value in the DataFrame

 

What's difference between array and list

 

Whats the difference between Gradient boosting and Xgboost

 

Is XOR data linearly separable

 

How do we classify XOR data using logistic regression

 

Some questions from my previous projects

 

Given a sand timer of 4 and 7 mins how would you calculate 10 mins duration.

 

What's the angle between hour and minute hand in clock as 3:15





Company: FISERVE

Role: Data Scientist

 

How would you check if the model is suffering from multi Collinearity?
What is transfer learning? Steps you would take to perform transfer learning.
Why is CNN architecture suitable for image classification? Not an RNN?
What are the approaches for solving class imbalance problem?
When sampling what types of biases can be inflected? How to control the biases?
Explain concepts of epoch, batch, iteration in machine learning.
What type of performance metrics would you choose to evaluate the different classification models and why?
What are some of the types of activation functions and specifically when to use them? 
What is the difference between Batch and Stochastic Gradient Descent?
What is difference between K-NN and K-Means clustering?
How to handle missing data? What imputation techniques can be used?




Company: Landmark group

Role: Data Scientist

 

Use Case - Consider you are working for pen manufacturing company. How would you help sales team with leads using Data analysis?
Interviewers ask about scenarios or use-case based questions to know interviewee thought process and problem-solving skills.
Assume you were given access to a website google analytics data.
In order to increase conversions, how do you perform A/B testing to identify best page design.
How is random forest different from Gradient boosting algorithm, given both are tree-based algorithm?
Describe steps involved in creating a neural network?
LSTM solves the vanishing gradient problem, that RNN primarily have. How?
In brief, how would you perform the task of sentiment analysis?




Company: Axtria

------------

1.RNN, NN and CNN difference.

Supervised, unsupervised and reinforcement learning with there algo example.
Difference between ai, ml and dl
How u do dimentionality reduction.
What is Multicollinearity
Parameters of random forest
7 . Parameters of deep learning algos

Different feature selection methods
Confusion matrix



Company: Latentview Analytics

Role: Data Scientist

Experience: 2 years

 

What is mean and median
Difference between normal and gaussian
distribution

What is central limit theorem
What is null hypothesis
What is confidence interval
What is covariance and correlation and how will u
interpret it.

How will you find out the outliers in the dataset
and is it always to remove outliers

Explain about Machine Learning
Explain the algorithm of your choice
Different methods of missing values imputation
Explain me your ml project
How did you handle imbalance dataset
What is stratified samplings
Difference between standard scalar and normal
scalar

Different type of visualization in Dl project
What architecture have you used
Why have u not used RNN in your nlp project
Why we don't prefer CNN in nlp based project
19 What is exploding gradient and vanishing gradient and how to rectify it

Difference between LSTM and GRU
What is precision and recall
22 What is auc metic

What if your precision and recall are same




What is Bias Variance Trade Off?




Company: Bridgei2i

Role: Senior Analytics Consultant

 

1)    What is the difference between Cluster and Systematic Sampling?

2)    Differentiate between a multi-label classification problem and a multi-class classification problem.

3)    How can you iterate over a list and also retrieve element indices at the same time?

4)    What is Regularization and what kind of problems does regularization solve?

5)    If the training loss of your model is high and almost equal to the validation loss, what does it mean? What should you do?

6)    Explain evaluation protocols for testing your models? Compare hold-out vs k-fold cross validation vs iterated k-fold cross-validation methods of testing.

7)    Can you cite some examples where a false positive is important than a false negative?

8)    What is the advantage of performing dimensionality reduction before fitting an SVM?

9)    How will you find the correlation between a categorical variable and a continuous variable ?

10)   How will you calculate the accuracy of a model using a confusion matrix?

11)   You are given a dataset with 1500 observations and 15 features. How many observations you will select in each decision tree in a random forest?

12)   Given that you let the models run long enough, will all gradient descent algorithms lead to the same model when working with Logistic or Linear regression problems?

13)    What do you understand by statistical power of sensitivity and how do you calculate it?

14)    What is pruning, entropy and information gain in decision tree algorithm?

15)    What are the types of biases that can occur during sampling?




Company: Prodapt Solutions

Role: Data Scientist

 

    Telecom Customer Churn Prediction. Explain the project end to end?
    Data Pre-Processing Steps used.
    Sales forecasting how is it done using Statistical vs DL models - Efficiency.
    Logistic Regression - How much percent of Customer has churned and how much have not churned? 
    What are the Evaluation Metric parameters for testing Logistic Regression? 
    What packages in Python can be used for ML? Why do we prefer one over another?
    Numpy vs Pandas basic difference.
    Feature on which this Imputation was done, and which method did we use there?
    Tuple vs Dictionary. Where do we use them?
What is NER - Named Entity Recognition?



Company: Landmark group

Role: Data Scientist

 

    SQL question on inner join and cross join
    SQL question on group-by
    Case study question on customer optimization of records for different marketing promotional offers
    Tuple and list
    Linear regression
    Logistic regression steps and process
    Tell me about your passion for data science? Or What brought you to this field?
    What is the most common problems you face whilst working on data science projects?
    Describe the steps to take to forecast quarterly sales trends. What specific models are most appropriate in this case?
  What is the difference between gradient and slope, differentiation and integration?
  When to use deep learning instead of machine learning. Advantages, Disadvantages of using deep learning?
  What are vanishing and exploding gradients in neural networks?
  What happens when neural nets are too small? What happens when they are large enough?
  Why do we need pooling layer in CNN? Common pooling methods?
  Are ensemble models better than individual models? Why/why - not?



Company: Mindtree

Role: Data Scientist

 

What is central tendency
Which central tendency method is used If there exists any outliers
Central limit theorem
Chi-Square test
A/B testing
Difference between Z and t distribution (Linked to A/B testing)
Outlier treatment method
ANOVA test
Cross validation
How will you work in a machine learning project if there is a huge imbalance in the data
Formula of sigmoid function
Can we use sigmoid function in case of multiple classification (I said no)
Then which function is used
What is Area under the curve
Which metric is used to split a node in Decision Tree
What is ensemble learning
3 situation based questions



Company: CodeBase Solutions

Role: Data Scientist

 

    What are the ML techniques you've used in projects?
    Very first question was PCA? Why use PCA?
    Types of Clustering techniques (Not algorithms)? Which Clustering techniques will you use in which Scenario - example with a Program?
    OCR - What type of OCR did you use in your project - Graphical or Non - Graphical?
    OCR - What is a Noise? What types of noise will you face when performing OCR? Handwritten can give more than 70% accuracy when I wrote in 2012 but you're saying 40%.
    Logistic Regression vs Linear Regression with a real-life example - explain?
    Is Decision tree Binary or multiple why use them?
    Do you know Map Reduce and ETL concepts?
    What is a Dictionary or Corpus in NLP and how do you build it? 
How do you basically build a Dictionary, Semantic Engine, Processing Engine in a NLP project, where does all the Synonyms (Thesaurus words go).
What are the Types of Forecasting? What are the ML and DL models for forecasting (He said Fast-forwarding models as example) other than Statistical (ARIMA) models you've used in your projects?
What is a Neural Network? Types of Neural Networks you know?
Write a Decision Tree model with a Python Program.
How do you build an AZURE ML model? What are all the Azure products you've used? I said Azure ML Studio.
Cibil score is an example for Fuzzy model and not a Classification model.
What is an outlier give a real life example? how do you find them and eliminate them? I gave an example of calculating Average salary of an IT employee. 



Company: Deloitte

Role: Data Scientist

 

    G values, P values, T values
    Conditional Probability
    Central Values of Tendency
    Can Linear Regression be used for Classification? If Yes, why if No why?
    Hypothesis Testing. Null and Alternate hypothesis
    Derivation of Formula for Linear and logistic Regression
    Where to start a Decision Tree. Why use Decision Trees?
    PCA Advantages and Disadvantages?
    Why Bayes theorem? DB Bayes and Naïve Bayes Theorem?
Central Limit Theorem? 
R packages in and out? For us it's Python Packages in and out.
Scenario based question on when to use which ML model?
Over Sampling and Under Sampling
Over Fitting and Under Fitting
Core Concepts behind Each ML model.
Genie Index Vs Entropy
how to deal with imbalance data in classification modelling? SMOTHE techniques



Verizon Data Science Interview Questions

 

    How many cars are there in Chennai? How do u structurally approach coming up with that number?
    Multiple Linear Regression?
    OLS vs MLE?
    R2 vs Adjusted R2? During Model Development which one do we consider?
    Lift chart, drift chart
    Sigmoid Function in Logistic regression
    ROC what is it? AUC and Differentiation?
    Linear Regression from Multiple Linear Regression
    P-Value what is it and its significance? What does P in P-Value stand for? What is Hypothesis Testing? Null hypothesis vs Alternate Hypothesis?
Bias Variance Trade off?
Over fitting vs Underfitting in Machine learning?
Estimation of Multiple Linear Regression
Forecasting vs Prediction difference? Regression vs Time Series?
p,d,q values in ARIMA models
    What will happen if d=0
    What is the meaning of p,d,q values?
Is your data for Forecasting Uni or multi-dimensional?
How to find the nose to start with in a Decision tree.
TYPES of Decision trees - CART vs C4.5 vs ID3
Genie index vs entropy
Linear vs Logistic Regression
Decision Trees vs Random Forests
Questions on liner regression, how it works and all
Asked to write some SQL queries
Asked about past work experience
Some questions on inferential statistics (hypothesis testing, sampling techniques)
Some questions on table (how to filter, how to add calculated fields etc)
Why do u use Licensed Platform when other Open source packages are available?
What certification Have u done?
What is a Confidence Interval?
What are Outliers? How to Detect Outliers?
How to Handle Outliers?
 

Company: L&T Financial Services

Role: Data Scientist

 

Explain your Projects
Assumptions in Multiple linear regression
Decision tree algorithm
Gini index
Entropy
Formulas of gini and entropy
Random forest algorithm
XGBoost Algorithm
Central Limit theorem
R2
Adj R2
VIF
Different Methods to measure Accuracy
Explain Bagging and Boosting
Difference Between Bagging and Boosting
Various Ensemble techniques
P value and it’s significance
F1 Score
Type 1 and Type II error
Logical questions for Type 1 and Type II error
Logical questions for Null and alternate Hypothesis



Role: Data Scientist

 

Decorators in Python
- Live Example

Generators in Python
- Live Example

 

SQL Questions
 

3.1 Group by Top 2 Salaries for Employees

3.2 use Row num and Partition

 

Pandas find Numeric and Categorical Columns.
4.1 For Numeric columns, find the mean of the entire column and add that value to each row of the column.

 

What is Gradient Descent?
5.1 What is Learning Rate and Why is it reduce sometimes

 

Two Logistic Regression Models - Which one will you choose - One is trained on 70% and other on 80% data. Accuracy is almost same.
What is LogLoss ?
 

Explain your Projects end to end.(15-20mins)





Role: Data Science Intern

 

Tell me about your journey as a Data Science aspirant
What was the one challenging project or task that you did in this domain and why was it challenging?
What model did you use for that? I replied Random Forests
What is Random Forest and how is it used?
How are Random Forest different from Decision Trees and what problems do they solve that decision trees can't?
Multi class Classification and which metric is preferred for it
Given a banking scenario to predict Loan Defaulters, which metric will you use?
How will you handle the class imbalance in this case?





Company: Latentview Analytics

 

What is mean and median
Difference between normal and gaussian
distribution

What is central limit theorem
What is null hypothesis
What is confidence interval
What is covariance and correlation and how will u
interpret it.

How will you find out the outliers in the dataset
and is it always to remove outliers

Explain about Machine Learning
Explain the algorithm of your choice
Different methods of missing values imputation
Explain me your ml project
How did you handle imbalance dataset
What is stratified samplings
Difference between standard scalar and normal
scalar

Different type of visualization in Dl project
What architecture have you used
Why have u not used RNN in your nlp project
Why we don't prefer CNN in nlp based project
19 What is exploding gradient and vanishing gradient and how to rectify it

Difference between LSTM and GRU
What is precision and recall
22 What is auc metic

What if your precision and recall are same



Data Science Interview Questions

 

Naive bayes assumptions
What are the approaches for solving class imbalance problem?
When sampling what types of biases can be inflected? How to control the biases?
GRU is faster compared to LSTM. Why?
What is difference between K-NN and K-Means clustering ?
How to determine if a coin is biased ? Hint: Hypothesis testing
How will u present the statistical inference of a particular numerical column?
How would you design a data science pipeline ?
Explain back propagation in few words and it’s variants?
Explain topic modeling in NLP and various methods in performing topic modeling.



Company: Myntra

Role: Data Analyst

 

Introduce yourself.

 

One complex sql query- 2 table are there, Table1(cust_id,Name) Table2(cust_id,Transaction_amt)

Write a query to return the name of customers with 8th highest lifetime purchase.

 

Achieve the same using python.

 

ML questions:

 

What's the problem in having multi collinearity in data set.

If there is business requirement to keep two corelated features in model, what would you do.

How would you deal with feature of 4 categories and 20% null values

 

Some questions based on my project.




Company: Nira Finance

Role: Data Scientist

 

Asked to explain my project.

Have you not done any classification problem as your Resume only mentions regression tasks.

 

Explain the working of Gradient boosting.

Difference between boosting and bagging.

 

What would you do when output is imbalanced.

What is more preferred over sampling or under sampling.

In what case under sampling a non harmful approach.

 

How would you measure the performance of models built on imbalanced dataset.

Whats the meaning of precision and recall.

 

Tell me about a task you did and are very proud of.

Do you have any questions for me

 

Post interview I was given a ML assignment to solve and submit within next 2 weeks.




Company: Myntra

Role: Data Analyst

Round type: Use case Round

 

Problem Statement:

 

Given 2 teams of Myntra namely:

 

Finance Team: They focus to take decisions which are Money driven.
 

Customer Experience Team : They focus to improve the Customer Experience with Myntra.
 

Whenever Customer places a refund request Myntra can process it in 2 different ways:

 

Directly accept the Return request.
 

Put the request on hold and verify the product for damages or manhandling by customer. Only if the products are found to be in proper state, accept the return.
 

Now, there is a conflict of opinion between these two teams.

Finance Team likes the 2nd option as it minimize the chances of loss.

 

But Customer Experience teams likes the 1st option as their main aim is to improve Customer Experience.

 

Now suppose you are part of the Customer Experience team. How would you convince the Finance team to follow the 1st step.

 

What kind of Data you would be looking for solving this task.

 

Is there any need for model building for this use case.





Company: Ericsson

Role: Data Scientist

 

Round No: 1st Round

 

How to reverse a linked list

 

Give a logistic regression model in production, how would you find out the coefficients of different input features.

 

What is the p- value in OLS regression

 

What's the reason for high bias or variance

 

Which models are generally high biased or high variance

 

Write code to find the 8 highest value in the DataFrame

 

What's difference between array and list

 

Whats the difference between Gradient boosting and Xgboost

 

Is XOR data linearly separable

 

How do we classify XOR data using logistic regression

 

Some questions from my previous projects

 

Given a sand timer of 4 and 7 mins how would you calculate 10 mins duration.

 

What's the angle between hour and minute hand in clock as 3:15






Company: Legato Health Technologies

Role: MLOps Engineer

Experience: 2-3 years

 

Round 2:

Complete ML technical stack used in project?

Different activation function?

How do you handle imbalance data ?

Difference between sigmoid and softmax ?

Explain about optimizers ?

Precision-Recall Trade off ?

How do you handle False Positives ?

Explain LSTM architecture by taking example of 2 sentences and how it will be processed?

Decision Tree Parameters?

Bagging and boosting ?

Explain bagging internals

Write a program by taking an url and give a rough code approach how you will pass payload and make a post request?

Different modules used in python ?

Another coding problem of checking balanced parentheses?





Role: Junior Data Scientist

 

1) Explain the architecture of CNN

2)If we put a 3×3 filter over 6×6 image what will be the size of the output image

3) What will you do to reduce overfitting In deep learning models

3) Can you write a program for inverted star program in python

4)Write a program to create a dataframe and remove elements from it

5) I have 2 guns with 6 holes in each, and I load a single bullet In each gun, what is the probability that if I fire the guns simultaneously atleast 1 gun will fire (atleast means one or more than one)

5) There are 2 groups g1 and g2, g1 will ask g2 members to give them 1 member so thay they both will be equal in number, g2 will ask g1 members to give them 1 member so thay they will be double of g1, how many members are there in the groups (I'm not sure of this question as I tried to solve but didnt get correct answer)




Data Science Interview Questions:

 

How do check the Normality of a dataset?
Difference Between Sigmoid and Softmax functions?
Can logistic regression use for more than 2 classes?
What are Loss Function and Cost Functions? Explain the key Difference Between them?
What is F1 score? How would you use it?
In a neural network, what if all the weights are initialized with the same value?
Why should we use Batch Normalization?
In a CNN, if the input size 5 X 5 and the filter size is 7 X 7, then what would be the size of the output?
What do you mean by exploding and vanishing gradients?
What are the applications of transfer learning in Deep Learning?
Why does a Convolutional Neural Network (CNN) work better with image data?




Data Science Interview Questions:

 

What is the Central Limit Theorem and why is it important?
What is the difference between type I vs type II error?
Tell me the difference between an inner join, left join/right join, and union.
Explain the 80/20 rule, and tell me about its importance in model validation.
What is one way that you would handle an imbalanced data set that’s being used for prediction (i.e., vastly more negative classes than positive classes)?
Is it better to spend five days developing a 90-percent accurate solution or 10 days for 100-percent accuracy?
Most common characteristics used in descriptive statistics?
What do you mean by degree of freedom?
Why is the t-value same for 90% two tail and 95% one tail test?
What does it mean if a model is heteroscedastic? what about homoscedastic?
You roll a biased coin (p(head)=0.8) five times. What’s the probability of getting three or more heads?
What does interpolation and extrapolation mean? Which is generally more accurate?





Data Science Interview Questions:

 

What the aim of conducting A/B Testing?
Explain p-value.
Explain how a ROC curve works?
What is pruning in Decision Tree?
How will you define the number of clusters in a clustering algorithm?
When to use Precision and when to use Recall?
What are the assumptions required for linear regression? What if some of these assumptions are violated?
How are covariance and correlation different from one another?
How can we relate standard deviation and variance?
Explain the phrase "Curse of Dimensionality".
What does the term Variance Inflation Factor mean?
What is the significance of Gamma and Regularization in SVM?




Data Science Interview questions:

 

How will you calculate the Sensitivity of machine learning models?

What do you mean by cluster sampling and systematic sampling?

Explain Eigenvectors and Eigenvalues.

Explain Gradient Descent.

How does Backpropagation work? Also, it states its various variants.

What do you know about Autoencoders?

What is Dropout in Neural Networks?

What is the difference between Batch and Stochastic Gradient Descent?

What are the different kinds of Ensemble learning?

What is entropy, information gain and gini index in decision tree classifier and regression?







Role: Data Scientist

 

What is central tendency
Which central tendency method is used If there exists any outliers
Central limit theorem
Chi-Square test
A/B testing
Difference between Z and t distribution (Linked to A/B testing)
Outlier treatment method
ANOVA test
Cross validation
How will you work in a machine learning project if there is a huge imbalance in the data
Formula of sigmoid function
Can we use sigmoid function in case of multiple classification (I said no)
Then which function is used
What is Area under the curve
Which metric is used to split a node in Decision Tree
What is ensemble learning



My Statistics Checklist before going for a Data Science Interview:

 

Inferential and descriptive Statistics
Sample
Population
Random variables
Probability Distribution Function
Probability Mass Function
Cumulative Distribution Function
Expectation and Variance
Binomial Distribution
Bernoulli Distribution
Normal Distribution
Z-score
Central Limit Theorem
Hypothesis Testing
Confidence Interval
Chi Square Test
Anova Test
F-Stats



Role: Data Scientist

 

What is central tendency
Which central tendency method is used If there exists any outliers
Central limit theorem
Chi-Square test
A/B testing
Difference between Z and t distribution (Linked to A/B testing)
Outlier treatment method
ANOVA test
Cross validation
How will you work in a machine learning project if there is a huge imbalance in the data
Formula of sigmoid function
Can we use sigmoid function in case of multiple classification (I said no)
Then which function is used
What is Area under the curve
Which metric is used to split a node in Decision Tree
What is ensemble learning
3 situation based questions




ompany: Legato Health Technologies

Role: MLOps Engineer

 

Round 2:

Complete ML technical stack used in project?

Different activation function?

How do you handle imbalance data ?

Difference between sigmoid and softmax ?

Explain about optimisers ?

Precision-Recall Trade off ?

How do you handle False Positives ?

Explain LSTM architecture by taking example of 2 sentences and how it will be processed?

Decision Tree Parameters?

Bagging and boosting ?

Explain bagging internals

Write a program by taking an url and give a rough code approach how you will pass payload and make a post request?

Different modules used in python ?

Another coding problem of checking balanced parentheses?





Company: Cerence

Role: NLU Developer

 

Question1 :

Write a function that take two strings as inputs and return true if they are anagrams of each other and false otherwise

e.g.

(hello, hlleo) --> true

(hello, helo) --> false

 

Question 2 :

Write a function that take an array of strings "A" and an integer "n",

that return the list of all strings of length "n" from the array "A" that can be constructed

as the concatenation of two strings from the same array "A"

e.g.

A = [dog, tail, sky, or, hotdog, tailor, hot] and n=6

output should be "hotdog" and "tailor"

 

Question 3 :

Given an array "arr" of numbers and a starting number "x",

Find "x" such that the running sums of "x" and the elements of the array "arr" are never lower than 1.

e.g.

arr = [-2, 3, 1, -5].

The running sums will be x-2, x-2+3, x-2+3+1 and x-2+3+1-5.

So, the output should be 4.





Company: GEOTAB

 

Python :

Is python a language that follows pass by value, or pass by reference or pass by object reference
What are lambda functions and how to use them
Difference between mutable and immutable objects with example.
What are Python decorators? Why do we use them
 

SQL :

What is the difference between Inner join and left inner join ?
What are window functions ?
What is the use of groupby ?
 

SQL Round

3 tables given as below:

 

TRIPS

trip_id

vehicle_id

start_time

stop_time

 

VEHICLE_MAKE

vehicle_id

make_id

 

MAKES

make_id

make_name

 

There is a table which contains vehicle trips. Trips are not necessarily in order.

 

There is a table which contains vehicle makes. Makes are not necessarily known.

 

PROBLEM: Write SQL code that provides the number of trips that started on September 1st, 2020 for each vehicle with a KNOWN make. 

Order the results by the trip count.

 

op

 vehicle_id | trip_count 

     4 |     2

     1 |     1

     2 |     1






Role: MLOps Engineer

 

1st round:-

Introduction

Current NLP architecture used in my project

How will you identify Data Drift? Once identified how would you automate the handling of Data Drift

Data Pipeline used

Fasttext word embedding vs word2vec

When should we use Tf-IDF and when predictive based word embedding will be advantageous over Tf-IDF

Metrics used to validate our model

In MongoDB write a query to find employee names from a collection

In Python write a program to separate 0s and 1s from an array- (0,1,0,1,1,0,1,0)





Company: Latentview.

 

Initial they had asked for the explaining the project which I had done. I explained the Customer prediction case . Then I was asked with python questions by sharing my screen.

 

How do you handle the correlated variables without removing them
Explain the SMOTE, ADAYSN technique
What is stratified sampling technique
Explain the working of random forest and xgboost
How do you optimise the Recall of your output
What are chisquare and ANOVA test
In python they asked for LOC,ILOC, how do you remove duplicate,How to unique values in column,
In SQL they asked for the query for having matches between different teams




Company: Myntra

Role: Data Analyst

 

Introduce yourself.

 

One complex sql query- 2 table are there, Table1(cust_id,Name) Table2(cust_id,Transaction_amt)

Write a query to return the name of customers with 8th highest lifetime purchase.

 

Achieve the same using python.

 

ML questions:

 

What's the problem in having multi collinearity in data set.

If there is business requirement to keep two corelated features in model, what would you do.

How would you deal with feature of 4 categories and 20% null values.






Company: Enquero Global

Role: Data Scientist

 

Previous job role and responsibilities

Problem statement of your project and How do you overcome challenges

How do you handle feature which had many categories.

When to use precision and recall.

What are outliers & how do you handle them

Joins, self joins, said me to write sql queries on self joins

How good your with python

Logic for reverse string.

Data collection- how do you collect data and data preprocessing.

Focused on EDA part

Have you deveployed any project in cloud if you which cloud you had used and how do you do that.

How do you interact with domain expertise and business analytics people.

How do you replace Missing values for continuous variables.

What is your largest data set you have handled till now and tell me size of dataset.

Overall Mostly focused on SQL, DATA COLLECTION, EDA, feature engineering and selection.





A continuous variable is having missing values, so how will you decide that the missing values should be imputed by mean or median?

What is PCA and what each component means? Also, what is the maximum value for number of components?

What is test of independence? How do you calculate Chi-square value?

When precision is preferred over recall or vice-versa?

Advantages and disadvantages of Random forest over Decision Tree?

What is the c hyperparameter in SVM algorithm and how it affects bias variance tradeoff?

What are the assumptions of linear regression?

Difference between Stemming and Lemmatization?

Difference between Correlation and Regression?

What is p-value and confidence interval?

What is multicollinearity and how do you deal with multicollinearity? What is VIF?

What is the difference between apply, applymap and map function in python?






Deloitte Interview :

 

Role: Data Scientist

Candidate Name: Wanted to remain anonymous

ROUND 1 :

 

Introduction

 

- Started with Classification particularly Imbalance , oversampling.

Which class should i oversample etc.

Telecom Churn Case Study Questions like Evaluation metric for imbalance data

what threshold to choose to diving the classes (0.5 in case of balanced else sensitivity / Specifivity etc.

What if i don't use SMOTE() for handling imbalance how should i select the threshold now (messed up by me, roc , auc etc) Ans = Presion - Recall Curve

 

- NLP Questions

Sentiment analysis, preprocessing like (TFID, BOW), Embeddings, stemming, Lemmatization

libraries in know : nltk, spacy

 

- Regression Preprocessing

answered outlier, missing value immputation, Distribution, dummies, multicolinearity etc

You have two highy co-related columns which one will you drop? : "Based on Business Problem i will see accordingly.", 

 

- Naive Bayes Explanation , Drawback of Naive Bayes(couln't answere drawback of Naive Bayes, 'Assume all are independent', him)

- Hand Gesture Recognition Techniques (End to End)

- Resource Timesheet Forecasting . (What is it?? what you do on this?, " Explained with a story based on what i do in TCS".

 

- Do you know any Boosting Algorithms : YES

where have you used?? in Telecom Churn and Healthcare Analytics by AV

 

- Gradient Descent (How it works)

 

- KNN related. How do we choose value of K ??




- Stastical Computing:

Type 1 and Type 2 error

Alternate name of Type 1 error (couldn't answer alternate name of Type 1 error, 'False +ive, him)

What is p-Value (Explaiend with the example of Linear Regression from statsmodel)

 

- Do you have exposure of TimeSeires analysis : NO (didn't ask anything and seems fine with him)
