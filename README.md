##1. Title

Assessing people’s food habits from several features

##2. Abstract

The paper focuses on the relations between diabetes prevalence and food habits, using data coming from various areas. We here propose to study the dependencies of several factors on food habits, by computing the typical food item purchased by people with given features. The features that we would like to focus on are age, gender and density (density meaning density of the area that the person lives in).
We will separate the population sample from which our dataset is built according to the features mentioned above, and try to extract interesting tendancies in each group. We'll also study the correlation of each of these features with food habits.

##3. Research questions

1. Are age, gender and density correlated with food habits?
2. Are these features correlated together?
3. Which of these features allow us to form the most representative clusters of food consumers?

##4. Proposed dataset
["Year osward grocery" dataset](https://drive.google.com/file/d/1rIMTE3HduTEy8wrNO4NxAGkUTrVWMMPp/view?usp=sharing) from the paper. We don't have the equivalent dataset at "Borough scale" and we fear that there might be too much variance if we choose a finer scale than wards. The data is already in a pretty practical format, but we might choose to turn density into a categorical feature (in a similar way to what has already been done with the age feature).