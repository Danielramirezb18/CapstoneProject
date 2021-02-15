# Sparkify - Capstone Project

This project consists of predicting the churn rate of a fictitious music streaming platform called "Sparkify", there is a big challenge due to the huge data set we work with, so we need to manipulate it using Apache Spark, then after all the process and structuring of the data, we will design relevant characteristics to achieve our objective. Then we will use Spark MLlib to build and test different network machine learning models with large data sets, this library will help us to improve the training process and model optimization, such as Cross Validaion and Grid Search.

<a href='https://danielrrb30.medium.com/the-importance-of-data-analysis-on-data-science-process-28513919b2d8'>Medium link</a>

# Dataset and libraries

## Dataset

<b>mini_sparkify_event_data.json:</b> this is a small part of the complete data set. It contains information on 226 different users and 286,500 rows with 18 columns, the data set includes demographic information and transactional data on user behavior on the platform.

## Libraries
### Data handling
<ul>
<li>pandas.</li>
<li>numpy.</li>
<li>pyspark.sql</li>
</ul>

### Visualize

<ul>
<li>seaborn.</li>
<li>matplotlib.</li>
</ul>

### Modeling

<ul>
<li>pyspark.ml</li>
</ul>

# Results

After procces de initial log dataset we obtain 11 processed features and visual intial analysis, test two diferren calsiification machine larning algoritms Random Fores and Logistic regresion algo perfomr a grid search to evaluate if we can optimize our result the final model achive a 8/% of acurrincy with a defualt Random Forest model.
