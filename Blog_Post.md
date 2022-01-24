<img src=https://user-images.githubusercontent.com/96918132/150175572-2937f3d3-8ec7-41dd-ba50-8ec1edb71da3.png width="600" height="400"/>

## How to predict a Heartdisease

As the first project for the nano degree as a data scientist at udacity I have been given the assignment to work on a dataset
of my choice and pose a few questions which are related to business or real-world applications.<br>

So where to begin. <br>
For starters I searched at [kaggle](https://www.kaggle.com/) for a fitting dataset. I have been looking for one which has 
at least 5 features and also a feature which depends more or less on all the other features. <br>
In the end I made the decison to use the [Heart Failure Prediction Dataset](https://www.kaggle.com/fedesoriano/heart-failure-prediction). <br>
It has 12 columns/features and one of them is the result of a heart disease or none, which depends on the other features. 


### Can a smart whatch help you assess your probability of a heart disease?

Well what could be a business or real-world applications which is based on the probability of a heart disease? <br>
Since health insurance companies can't deny you coverage or raise your rates based only on your health I had to think of something else.
The next best thing that came to my mind then was the data a smart watch can record and which missing parameters could help it.
For starters we look at the base parameters age and sex which are easily easily acquired at health apps.
1. What is the probability of a heart disease for men and women based on their age?

2. Can the data from a smart watch (which records the heart ratio and the blood pressure) increase <br>the accuracy of the model from question 1?

3.  Which other of the features complements the already used features best?


### What do we need to answer these questions?
For once we need a base understanding of the dataset. A good way for that is the use of
a heatmap, which shows us the correlation between each feature.<br>
![grafik](https://user-images.githubusercontent.com/96918132/150194474-ac7ab83b-0714-47be-b6fc-94d49b45dfe4.png)<br>
The most interesting line for us is the last one. For my questions the features "Age, "Sex", "RestingBP", "MaxHR" and "ST_Slope" are of interest and
most of them show relatively good Pearson correlation.

For the model I implemented the fitting model from [Jason Brownlee](https://machinelearningmastery.com/how-to-connect-model-input-data-with-predictions-for-machine-learning/), which uses logistic regression.

### Results
The here used model showed an accuracy of 69% with just the two inputs age and sex. This increased to 71%
with the input from a possible smart watch and went up to 82% with the feature ST slope.<br>
![grafik](https://user-images.githubusercontent.com/96918132/150199518-b6a36951-fc3a-46e7-b0cb-8ead919c35e4.png)


To see more about this project, see the link to my Github [here]().
