The dataset contains 375000 records about crowdfunding worldwide projects data from 2010 to 2018; it has 15 features and an imbalance rate of 35% on positive class,
namely the success of a project. My goal is to discover those key characteristics that increase the probability of success of a campaign and those factors that most influence investors. To do
this, efforts were concentrated on a multivariate analysis of the data in order to discover possible correlations and trends, and a predictive analysis, training classification and regression models
and extrapolating their feature importance. Given the large size of the dataset, the Apache Spark framework was used to conduct the analyses.


In my analysis, I've uncovered insightful trends in crowdfunding projects from 2011 to 2018. Through data exploration, I've noticed significant shifts in the ratio between fundraisers and backers, 
particularly in niche categories like dance, theater, and comics. Surprisingly, I've found that title words and punctuation don't seem to impact investor participation. Moreover, I've identified
project duration and goal amount as crucial variables affecting project success, with shorter to medium durations and moderate goals being optimal. However, I've faced challenges with my
classification models in predicting campaign outcomes, highlighting the difficulty of achieving high accuracy due to the limited availability of project information.
