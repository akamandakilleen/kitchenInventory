# Kitchen Inventory
by Amanda Killeen

Project Presentation on [YouTube](https://youtu.be/IGDTl3qgO_E)

Tableau Dashboard on [Tableau Public](https://public.tableau.com/views/KitchenInventory_16194031448520/KitchenInventory?:language=en-US&:display_count=n&:origin=viz_share_link)

## Project Goal
Taking the concept of reverse grocery list, where you have a list of things you normally buy and figure out what you are out of, I have built a database and dashboard showing which items I have on hand in my kitchen and where inventory is running low, and map which stores I need to visit, so that I stay within budget, don’t over purchase, and can plan meals accordingly. 

Using USDA food and brand data, this inventory tracks attributes such as where the food is stored (e.g. Pantry, Fridge, Freezer), category, brand, quantityOnHand, quantityNeeded and more. In addition to tracking the items, it flags when inventory is low and the item needs to be purchased.  

This project was an opportunity to apply my database and SQL skills to parse a dataset into multiple relations efficiently as part of my Database Systems and Design course at the University of Colorado, Boulder.

## Tools
- DataGrip - Database & SQL IDE.  This was the main tool I used to create tables and write queries before transferring them to JupyterLab.
- JupyterLab + Python - Final report write-up
- SQLAlchemy - Handles database connection and query execution in Python
- Pandas - Used for query output, for better table visuals than SQL output.
- Tableau - Data visualization tool for creating visualizations related to the database, including the mapping of stores and item inventory status.
- CSV file Inventory -  A single table will all inventory data data to be parsed into multiple relations using SQL.
- MySQL - SQL dialect to be used in creation and management of database
- Google Cloud Platform - Database hosting platform

## Datasets
- [Branded Foods - October 2020](https://fdc.nal.usda.gov/download-datasets.html): Foods with associated brand names
    - branded_food.csv
    - food.csv
- [FNDDS 2017-2018 - October 2020](https://fdc.nal.usda.gov/download-datasets.html): Generic Foods (produce, dairy, meat)
    - food.csv
