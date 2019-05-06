# CS-581---Ride-Sharing-Project

This project implements and evaluates a ride sharing algorithm on spatio-temporal data. NYC taxi cab 2016 data has been used for evaluations. The aim is to be able to merge individual taxi trips with the hope of saving mileage as well as time.

To run the project:
- Use the following link to download data.zip and data.json.zip files
- Unzip the data.zip and data.json.zip file to obtain the data folder and data.json file. Place them in the same directory as that of the other two Python notebooks
- Create a locate MySQL database and also a table to store the processed data. The schema for the table is mentioned in the Database.ipynb notebook
- Run the Database.ipynb notebook first which essentialy takes all the trips data month by month and performs the preprocessing steps. It also finally stores the processed data in the table created in above step.
- Run the DBMS-ride-sharing-final.ipynb notebook in a sequential manner using the instructions provided within the notebook to get the merged rides output.
