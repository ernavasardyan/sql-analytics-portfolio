# Sql-analytics-portfolio

## Building Dummy Database for Testing

Step 1. Create a new repository on https://github.com

Step 2. In the terminal, write git clone and add the repository link.
Step 3. Create a new folder on your computer named ACA.
Step 4. Download the database and place it into the newly created folder.
Step 5. Open VS Code and write:
git add and git commit -m "Added data folder with csv datasets"
Step 6. Go to https://github.com
, open your .gitignore file, and add the following: Pgadmin_data and postgres_data.
Then in VS Code again run git add and git commit -m.
Step 7. In VS Code create two folders with the following names: 01_schema sql and 02_etl sql, and add the code from
https://hovhannisyan91.github.io/aca/materials/sql/session1.html#building-our-first-database

into them. Then again run git add and git commit -m.
Step 8. In VS Code create a file named .env, and inside it add the data from the same link
https://hovhannisyan91.github.io/aca/materials/sql/session1.html#building-our-first-database

Then again run git add and git commit -m.
Step 9. In VS Code create a file named docker compose yaml, add the code from the same link, and again run git add and git commit -m.
Step 10. In the terminal run docker compose up, go to http://localhost:5050
, enter your credentials, and log in.
Step 11. Inside there, create a server using the required details from the link. After entering the server, find your tables and view your database.