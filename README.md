# nosql-challenge
_Bootcamp: UPENN-VIRT-DATA-PT-06-2023-U-LOLC-MTTH Module 12 NoSQL Challenge

## Description
This challenge is broken into three parts over two Jupyter notebooks:

### NoSQL_setup
This notebook contains Part 1: Database and Jupyter Notebook Set Up and Part 2: Update the Database.
Part 1 imports the necessary modules and creates a link between the notebook and the database using Mongo Client.

Part 2 includes code to add a restaurant to the database (Penang Flavours).
It also updates the `latitude`, `longitude`, and `RatingsValue` fields from strings to doubles/floats or integers.

### NoSQL_analysis
This notebook contains Part 3: Exploratory Analysis.
It focuses on generating queries to answer the following questions.

1. Which establishments have a hygiene score equal to 20?
1. Which establishments in London have a RatingValue greater than or equal to 4?
1. What are the top 5 establishments with a RatingValue of 5, sorted by lowest hygiene score, nearest to the new restaurant added, "Penang Flavours"?
1. How many establishments in each Local Authority area have a hygiene score of 0? Sort the results from highest to lowest, and print out the top ten local authority areas.

The resulting data from each query is stored in a pandas DataFrame


## Installation/Instructions
### Requirements
This project was run with the following programs/packages:

- Python 3.11
- Jupyter 1.0.0
- Pandas 1.5.3
- mongodb-community@6.0 6.0.6


### Output
All output is stored as output in the two Jupyter notebooks [NoSQL_setup](NoSQL_setupipynb.ipynb) and [NoSQL_analysis](NoSQL_analysis.ipynb).

## Credits
[UK Food Standards Agency](https://www.food.gov.uk/) (2022). UK food hygiene rating data API. <https://ratings.food.gov.uk/open-data/en-GB>. Contains public sector information licensed under the [Open Government Licence v3.0](https://www.nationalarchives.gov.uk/doc/open-government-licence/version/3/)
Accessed Sept 9, 2022 and Sept 12, 2022 with the establishment settings as follows: longitude=51.5072, latitude=-0.1276, maxdistancelimit=4567, pagesize=10000, sortoptionkey=distance, pagenumber=(1,2,3,4,5,6,7,8).

## License
[MIT LICENSE](LICENSE)
