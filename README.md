## 1. Title

Assessing people’s food habits from several features

## 2. Abstract

The paper focuses on the relations between diabetes prevalence and food habits, using data coming from various areas. We here propose to study the dependencies of several factors on food habits, by computing the typical food item purchased by people with given features. The features that we would like to focus on are age, gender, and density (density meaning density of the area that the person lives in). We'll also study the correlation of these features with the mean income of the inhabitants of a given area.

We will separate the population sample from which our dataset is built according to the features mentioned above, and try to extract interesting tendencies in each group. We'll also study the correlation of each of these features with food habits.

## 3. Research questions

1. Are age, gender, density and income correlated with food habits?
2. Are these features correlated with each other?
3. Which of these features allow us to form the most significant clusters of food consumers?

## 4. Proposed datasets

- ["Year MSOA grocery" dataset](https://drive.google.com/file/d/1WfnebCsuTOXvI3pGrWLxk705BlnE_oem/view?usp=sharing) from the paper. We think this scale is fine enough to give us interesting insights, and broad enough for us to get enough data for our experiments. The data is already in a pretty practical format, but we might choose to turn density into a categorical feature (in a similar way to what has already been done with the age feature).
- ["Income estimates MSOA"](https://data.london.gov.uk/dataset/ons-model-based-income-estimates--msoa), a dataset published by the ONS which will give us insights on the incomes of the inhabitants of each MSOA.