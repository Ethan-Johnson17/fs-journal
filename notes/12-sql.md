# SQL
MongoDB is noSQL, MySQL is not.
MySQL can take two string data types: VARCHAR (you set length) and TEXT (automatically sets at max length). 

.env is now appsettings.Development...
You can create a new table in dbSetup.sql and run it. Ensure that your db is active in the util bar below.
End of a sql statement needs a ; --> sql @" ... ;";
Dapper does not like constructors. Models will no longer include them.
We now need a transient for the repository

SELECT
    car.*,
    account.*
    FROM cars car
    JOIN accounts account ON car.creatorId = account.id