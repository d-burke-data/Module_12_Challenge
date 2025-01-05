# Module_12_Challenge : *NoSQL Challenge*
  
This repository concerns analysis of restaurants in the United Kingdom. The data was collected from the UK Food Standards Agency via its API in 2022. This data was imported into a MongoDB database, which was then used along with Pandas in Python to answer several exploratory analysis questions. Answers to these questions are provided in the Jupyter Notebook *NoSQL_analysis.ipynb*.
  
## Exploratory Analysis Questions
1. Which establishments have a hygiene score equal to 20?
2. Which establishments in London have a `RatingValue` greater than or equal to 4?
3. What are the top 5 establishments with a `RatingValue` of 5, sorted by lowest hygiene score, nearest to the new restaurant added, "Penang Flavours"? (See *NoSQL_setup.ipynb*)
4. How many establishments in each Local Authority area have a hygiene score of 0?
  
## Relevant Files

Python (Jupyter Notebooks):
+ NoSQL_setup.ipynb *(Jupyter Notebook for creating and updating the MongoDB database)*
+ NoSQL_analysis.ipynb *(Jupyter Notebook for exploratory analysis)*

## Data Source
UK Food Standards Agency (2022). UK food hygiene rating data API. https://ratings.food.gov.uk/open-data/en-GB. Contains public sector information licensed under the Open Government Licence v3.0.
Accessed Sept 9, 2022 and Sept 12, 2022 with the establishment settings as follows: longitude=51.5072, latitude=-0.1276, maxdistancelimit=4567, pagesize=10000, sortoptionkey=distance, pagenumber=(1,2,3,4,5,6,7,8).
