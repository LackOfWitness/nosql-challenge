<div align="center">
  <img src="UK Food ReadMe Presentation Graphic.png" alt="UK Food Standards Agency Data Analysis" style="border: 2px solid #ddd; border-radius: 8px; box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);">
</div>

# UK Food Standards Agency Data Analysis

## Overview
This project analyzes food hygiene rating data from the UK Food Standards Agency. It uses MongoDB to store and query the data, and Python with PyMongo for data manipulation and analysis.

## Features
- Database setup and data import
- Exploratory data analysis
- Geospatial queries
- Data aggregation and statistical analysis

## Technologies Used
- Python
- MongoDB
- PyMongo
- Pandas
- Jupyter Notebook

## Setup and Installation
1. Ensure MongoDB and Mongoshell are installed and running on your system.

2. Utilize Mongosh shell code (`database_import_code.md`) to load the data from the `establishments.json` file into the database. This step is crucial for populating the MongoDB with the necessary data for analysis.

3. Ensure you have the following libraries and packages installed:
   - pymongo library: For MongoDB interaction
   - pandas library: For data manipulation and analysis
   - jupyter library: For running Jupyter notebooks
   - pprint library: For pretty-printing complex data structures

4. Clone this repository to your local machine.

## Usage
1. Open the Jupyter Notebooks:
   - `NoSQL_setup_starter.ipynb`: For database setup and initial data import
   - `NoSQL_analysis_starter.ipynb`: For data analysis and queries

2. Run the cells in each notebook sequentially to perform the analysis.

## Key Findings
- Distribution of hygiene scores across different establishments
- Identification of establishments with high ratings in specific geographic areas
- Analysis of establishments with low hygiene scores by local authority

## Future Work
- Incorporate more recent data for trend analysis
- Develop a dashboard for interactive data exploration
- Expand analysis to include other factors affecting food hygiene ratings

## Data Source
UK Food Standards Agency (2022). UK food hygiene rating data API. https://ratings.food.gov.uk/open-data/en-GB. Contains public sector information licensed under the Open Government Licence v3.0.

Accessed Sept 9, 2022 and Sept 12, 2022 with the establishment settings as follows: longitude=51.5072, latitude=-0.1276, maxdistancelimit=4567, pagesize=10000, sortoptionkey=distance, pagenumber=(1,2,3,4,5,6,7,8).

## License
This project is licensed under the MIT License - see the LICENSE file for details.