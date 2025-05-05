# ChatDB

This porjects included two databases, one SQL (MySQL) and one NoSQL that can both be interacted with using Natural Language.

The MySQL database includes golf data, which includes course data, leaderboard data, and player statistics. Sample data is included in the SQL folder. Sample data includes data from 2024 and 2023 only. 

The NoSQL database includes NBA data, which includes player season totals, player statistics, and team totals. Sample data is included in the NoSQL folder. Sample data includes data from 1947 to 2025.


# Instructions

To create this application locally must create your own MySQL and MongoDB databases.

MySQL: 

1. Created a MySQL database, add your connection to the Upload_Data.py script
2. After the connection is added, run the script, ensure the sample data is in the same folder. 
3. After the script is successsfully ran, all the sample data shoould be inserted into the MySQL DB you specified. 


NoSQL:

1. Created a MongoDB database, add your connection to the PyMongo.py script. Note the CSV2JSON script is only there if the data is in CSV format, we have already converted the data provided
2. After the connection is added, run the script, ensure the sample data is in the same folder. 
3. After the script is successsfully ran, all the sample data shoould be inserted into the MongoDB DB you specified.


ChatDB:

1. For this you need a OpenAI api token, if you dont already have one you can get one here https://platform.openai.com/docs/overview
2. Once you have created a token insert it into the specified location in the ChatDB.py file, along with your connections for the MySQL and MongoDB databases
3. After, you can either run the script in the command prompt (preferred) by navigating to the folder (cd folder path) and typing python ChatDB.py. Or run it in you IDE and interact with the chatbot in the terminal
