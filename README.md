# Crowdfunding_ETL

## Part 1: ETL Mini Project
In this part of the project, the crowdfunding.xlsx and contacts.xlsx files were imported to extract, process, and clean data to transform it into CSV files that are ready to be loaded using pgAdmin. This data transformation process is performed through a Jupyter notebook file named ETL_Mini_Project.ipynb. The outputs of this process are four CSV files as follows:

- campaign.csv
- contacts.csv
- category.csv
- subcategory.csv
  
## Part 2: Load CSV Files Using pgAdmin
An Entity-Relationship Diagram (ERD) was generated using QuickDBD to represent the database structure. The commands for creating this ERD are included in the QuickDBD_ERD.txt file, and you can find the exported PNG file within this repository.

The schema for the four entities in the database is saved as crowdfunding_db_schema.sql. This schema defines the structure of the database tables and their relationships.

Finally, the four CSV files were imported into the database tables using pgAdmin. The correctness of the import was verified by running SELECT * FROM commands on each table to ensure the data was successfully loaded.

## QuickDBD ERD
![ERD](https://github.com/GwendolineGrenu/Crowdfunding_ETL/blob/main/ERD_PNG.png)
