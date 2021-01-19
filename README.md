# Airbnb-Rental-Price-prediction
# Table of Contents

1. Installation
2. Project Motivation
3. File Descriptions
4. Results
5. Licensing, Authors, and Acknowledgements

# Installation
You will need the standard data science libraries found in the Anaconda distribution of Python (Pandas, Numpy, Matplotlib, Seaborn, SciKit-Learn...)

# Project Motivation
For this project, I was interestested in analyzing data from AirBnB homes located in Montreal and Toronto. Specifically, I looked at the following questions:

- How much do people charge to rent their homes? How does this compare from Montreal to Toronto?
- What is the ideal time to visit Montreal and Toronto?
- Which areas of Montreal and Toronto are the most expensive and which area is the most rated?
- What are the main factors that influence Airbnb renting price?

# File Descriptions
The following are the files available in this repository:

` AIRBNB_Rental_Prices_Analysis_ Montreal_Vs_Toronto.ipynb`  - a notebook of the analysis performed following the CRISP-DM process

` calendar_m.csv`  and ` calendar_t.csv`  - csvs containing home_id, date, availability, and price for each home

` listings_m.csv`  and ` listings_t.csv`  - csvs containing id (listing ID), name (name of the listing), host_id (host ID), host_name (name of the host), room_type (listing space type), and price (price in dollars).

` reviews_m.csv`  and ` reviews_t.csv`  - csvs containing the home_id, date of review, reviewer_id, reviewer_name, and reviewer comments for the reviewed stays.

# Results
The main findings of the code can be found at the blog post available [here](https://medium.com/@imane.datax/airbnb-rental-prices-analysis-montreal-vs-toronto-c405f698a314).

# Licensing, Authors, Acknowledgements
Must give credit to AirBnB for the data. You can find the Licensing for the data and other descriptive information for the Montreal and Toronto data on [AirbnbInside](http://insideairbnb.com/get-the-data.html).
