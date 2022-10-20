# Crowdfunding-ETL_bootcamp
The Module 8 Challenge for the UNC data analysis bootcamp.

In Extract-Transform_final_code.ipynb, we extract unclean data from a backer_inf.csv file and transform it into a usable state. We do it both via the json python module and using regex. We export the clean data in backers.csv for further use.

Using crowdfunding_db_schema.sql, we create tables in postgreSQL to hold backers.csv, campaign.csv, category.csv, contacts.csv, and subcategory.csv according to the schema shown in crowdfunding_db_relationships.png.

Using the code from crowdfunding_SQL_Analys.sql, we create (and export) the tables email_contacts_remaining_goal_amount.csv and email_backers_remaining_goal_amount.csv, per the challenge instructions.
