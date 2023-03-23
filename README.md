

First, we will create a database, tables and insert some data.

Second, we develop APIs using ASP.NET Core Web API.

Third, we develop the frontend using angular 12.

Step 1 - (Database Related Activities)

install Mysql and SQL Server Management Studio in you local system .

After opening SQL Server Management Studio and connecting to a local database, create a database named StudentDB.
and run mentiond query

"  CREATE DATABASE StudentDB;
    CREATE TABLE dbo.Student (
    StudentId int IDENTITY(1,1) NOT NULL,
    FullName nvarchar(max) NULL,
    Class nvarchar(max) NULL
    );

  INSERT INTO dbo.Student VALUES ('Amit Rana', 'xyz');
  INSERT INTO dbo.Student VALUES ('Rohit Sarker','Xyz');
"

follow same step for department also 

run API and then Angular project for UI adding link 
https://github.com/Amitrana12/EmpolyeeDetails
