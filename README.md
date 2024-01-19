# Project---3
This project was an exploration through the World Happiness Report and applying user-driven visualizations.
The purpose of this project was to demonstrate a thorough understanding of topics covered in class and the 
ability to learn a new library not covered in class independantly.

Group members include Ben Brown, Don Ricumstrict, Drew Doran, and Khrystyne Clifton.

----------------------------------------------------------------------------------------------------------------

To interact with the project-
Please be sure to download:
All Dependencies files, Presentables.ipynb	

In your Jupyter notebook please run all cells.
Feel free to scroll through and interact with maps and their associated dropdowns, search bars, zoom, and popups.

----------------------------------------------------------------------------------------------------------------

Ethical concerns:
Due to the fact that the responses to the Gallup poll that created this data set were entirely voluntary and the 
data is publicly available, there were no concerns about accessing the data available.

Ethical concerns arise primarily in how data is presented. We do not want to compare countries to countries since 
they are all the homes of someone and we do not want anyone feeling poorly about their home. For the purpose of 
comparison, many of the years datasets had a column for “Dystopia Residual”. The purpose of this column was to 
give a baseline for the most miserable (imaginary) country in the world that countries’ scores could be compared 
to (See https://www.kaggle.com/datasets/unsdsn/world-happiness for more info on Dystopia Residuals).

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
