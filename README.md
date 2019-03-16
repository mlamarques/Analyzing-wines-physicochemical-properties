# Analyzing-wines-physicochemical-properties

This is a project I made for the Udacity Data Scientist Nanodegree program.
The data used for the project was suggested by Udacity and can be found [here]
(http://www3.dsi.uminho.pt/pcortez/wine/) All the analysis was made in RStudio
and the final work can be seen in the html file _projecttemplate.html_.

## Version
RStudio version **1.1.453**

## Libraries
- ggplot2
- GGally
- tidyr
- purr
- gridExtra

## Data

I'm using the public dataset **Wine Quality Datasets** - P. Cortez, A. Cerdeira,
F. Almeida, T. Matos and J. Reis. Modeling wine preferences by data mining from
physicochemical properties. In Decision Support Systems, Elsevier,
47(4):547-553, 2009. It contains two datasets, one for red wines and another
for white wines. In this project I'm using the white wine dataset.

The dataset uses the measurements of 13 chemical constituents from
[Vinho Verde Wines](http://www.vinhoverde.pt/), a wine brand from the northwest
region of Portugal.

#### Features

- Fixed acidity: g(tartaric acid)/dm3
- Volatile acidity: g(acetic acid)/dm3
- Citric acid: g/dm3
- Residual sugar: g/dm3
- Chlorides: g(sodium chloride)/dm3 the amount of salt in the wine
- Free sulfur dioxide: mg/dm3
- Total sulfur dioxide: mg/dm3
- Density: g/cm3
- pH
- Sulphates:g(potassium sulphate)/dm3
- Alcohol: % vol.
- Quality:  evaluated by a minimum of three sensory assessors
(using blind tastes), classified in a scale from 0 (very bad) to 10 (excellent).
The final sensory score is the median of these evaluations.
