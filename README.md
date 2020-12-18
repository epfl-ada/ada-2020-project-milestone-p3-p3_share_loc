## 1. Title

Assessing people’s food habits and healthiness

## 2. Abstract

The paper focuses on the relations between diabetes prevalence and food habits, using data coming from various areas. We here propose to study the dependencies of several factors on food habits, by computing the typical food item purchased by people with given features. The features that we would like to focus on are age, gender, and density (density meaning density of the area that the person lives in). We'll also add a feature extracted from a new dataset: the average income of the inhabitants of a given area.

We will compute the correlation of these features with people's food habits (meaning the average content of the food items that they purchase). We'll also study the correlation of each of these features with with each other.

Finally, using the diabetes prevalences that are given in the article and that we replicated, we'll classify the population into clusters of healthiness, considering that the lower your chances are of getting diabetes, the healthier your food habits are.

## 3. Research questions

1. Are age, gender, density and income correlated with food habits?
2. Are these features correlated with each other?
3. Which of these features allow us to form the most significant clusters of food consumers?

## 4. Proposed datasets

- ["Year MSOA grocery"](https://drive.google.com/file/d/1WfnebCsuTOXvI3pGrWLxk705BlnE_oem/view?usp=sharing) dataset from the paper. We think this scale is fine enough to give us interesting insights, and broad enough for us to get enough data for our experiments. The data is already in a pretty practical format, but we might choose to turn density into a categorical feature (in a similar way to what has already been done with the age feature).
- ["Income estimates MSOA"](https://data.london.gov.uk/dataset/ons-model-based-income-estimates--msoa), a dataset published by the ONS which will give us insights on the incomes of the inhabitants of each MSOA.
- ["Diabetes estimates osward"](https://drive.google.com/file/d/1YKeBEbyyu9wo0NCA1wLxHz-SfIKecV4o/view?usp=sharing), the dataset used in the paper to compute the diabetes prevalences from the food habits.

## 5. Methods

We'll use several tools to estimate the correlations described above:
- Spearman correlations, to find out which of our features are the most relevant, and to see if they are correlated with one another.
- Regression (linear regression, random forest), to estimate the food habits of a person with given features.
- Pie charts, to plot the distribution of nutrients in the typical food item purchased by a person with given features.
- Classification (probably random forest), to determine in which kinds of people can be considered "healthy", "average" or "unhealthy".

## 6. Proposed timeline and organization within the team

This is the task breakdown that we propose for our work, with the "due date" and person responsible for each of them:
- 30 nov: Data wrangling and preprocessing (Charles)
- 11 dec: Models, plots and figures (spearman correlations, regression, pie charts, classification) (Ulysse + Charles)
- 16 dec: Interpretations (choosing relevant plots and finding links between them) (Ulysse + Mouhannad)
- 18 dec: Report (Mouhannad)
- 23 dec: Video (Charles)

## P4 update: Members contributions

- Charles: Data wrangling, minor EDA, wrote part of the plots interpretation
- Mohanad: Plots, conclusion of the data story
- Ulysse: EDA, model elaboration and plots, set up the webpage and structure of the data story