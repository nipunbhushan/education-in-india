# Education in India
A dive-in into the possible factors affecting the literacy rate in different states of India. Literacy level is an important factor to how we see the development of that region/city/state or country as a whole, as literacy directly affects nearly all the factors that support the development of the country.  People having low literacy rate will often get affected on the economic (poverty), employment, social (fertility rate etc.) factors which would directly affect the development of the region and thus the contry as a whole.

Analysing the states with high and low literacy rates will allow us to  study the factors which significantly affect the quality of education and thus the literacy rates. 

#### Data Files:
The data files have been gathered from different sources:
+ Kaggle - The information on the schools, facilities, teachers, their qualification, students.
+ Census India 2011 - The Census website for capturing the demographic Data for the different states along with information of Employment, Fertility Rate, Education level for different age groups, their literacy level etc.

**data_files**  contain the raw data files received from Kaggle whereas **transformed_files** contain the *cleaned and transformed* version of the files received from both Kaggle and the Census. So basically, we use all the files present in the **transformed_files** for our analysis. As a standard flow, the cleaned files were pushed into the MySQL database and was later retrieved from there to perform the analysis.

#### Python Scripts:

    education-in-india-infrastructure.ipynb

contains the script for transforming the files received from Kaggle (statistics on the schools, their facilities etc.) and pushing the cleaned data into MySQL DB.

    education-in-india-parameters.ipynb

contains the script for transforming the files received from Census and pushing the cleaned data into MySQL DB.

#### Exploratory Data Analysis | TABLEAU:

The **EDA** has been performed on Tableau. The link to Tableau Visualization Page is as below:

https://public.tableau.com/app/profile/nipun.bhushan/viz/education_in_india/Story

#### Presentation Slides:

The presentation slides are located in the **ppt_files** folder.
