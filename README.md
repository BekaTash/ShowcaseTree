# ShowcaseTree
Tree Census Data Analysis Project

Overview:

This project focuses on a comprehensive data analysis workflow using Python. We'll walk you through the steps we took to analyze the Tree Census data from New York City and San Francisco. This includes data acquisition, cleaning, integration, analysis, and visualization.

Project Structure
The project is organized as follows:

Data Acquisition:

We collected data from two sources - New York City Tree Census API and a static dataset from San Francisco's Tree Census.
Due to memory limitations, we limited the NYC API to 300,000 records.
Data Cleaning:

We converted data to appropriate formats, handling missing values.
Renamed and standardized common tree species names for consistency.
Data Integration:

We merged the datasets and focused on the top 10 species shared by both regions.
Data Analysis:

Explored the distribution of tree diameters.
Investigated health status across boroughs.
Mapped tree locations using coordinates.
Examined similarities and differences between the two cities' tree populations.
Data Persistence:

We stored the cleaned data in two formats: SQLite and HDF5 for easy access and future analysis.

Resources
Link to NYC Tree Census Data - https://data.cityofnewyork.us/Environment/2015-Street-Tree-Census-Tree-Data/uvpi-gqnh
Link to SF Tree Census Data - https://data.sfgov.org/City-Infrastructure/Street-Tree-List/tkzw-k3nq
