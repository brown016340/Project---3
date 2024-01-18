# Project---3
This project was an exploration through the World Happiness Report and applying user-driven visualizations.

Group members include Ben Brown, Don Ricumstrict, Drew Doran, and Khrystyne Clifton.





----------------------------------------------------------------------------------------------------------------
Data Wrangling:
2018 and 2019 had a column titled "Social Support" whereas 2015-2017 had the title "Family" for the equivalent
colum.
We retitled 2018 and 2019 columns to Family.

Coords.csv created due to long runtime for searching for countries' coordinates.

Unrecognized countries: Hong Kong, north Cyprus, somaliland region.

Unrecognized countries had to be hard coded for GeoPy.

During the merge process, some countries were spelled with or without capitalization on some words and had to be
changed over manually.
----------------------------------------------------------------------------------------------------------------
Code runs best in actual jupyter notebook, not in VS Code.






----------------------------------------------------------------------------------------------------------------
Data housed in SQL, accessed via SQLalchemy

Data sourced from:
https://datahub.io/core/geo-countries#resource-countries
https://www.kaggle.com/datasets/unsdsn/world-happiness
