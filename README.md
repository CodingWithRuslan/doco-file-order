# doco-file-order
## 3.Step-by-Step Guide to Build the Beer Factory Project
    -create new database
    -create new table for that database
    -insert entries into the table created
    
# 3.1.Setting Up the Database:
      -  1.  To Access phpMyAdmin to manage databases, visit url https://localhost/phpmyadmin/:
  .![image](https://github.com/user-attachments/assets/54e01802-8b4e-4a6d-9584-7aabdf739431)
  
      -  2.  To Create New Database(2 ways): 1.Click New on the left sidebar. 2.Click on Databases tab on the top of the page navbar(both give same result):
  .![image](https://github.com/user-attachments/assets/38b7a60b-42b1-432c-b3f0-9fb93008deb9)
  
      -  3.  Name the Database beer_factory_db and utf8mb4_general_ci after that click on Create button.
  Name the Database beer_factory_db and utf8mb4_general_ci after that click on Create button. ![image](https://github.com/user-attachments/assets/4a765ade-3271-4d52-819c-08ceabfaf8fd)   
        After pressing Create button: ![image](https://github.com/user-attachments/assets/c3bd42f9-9f8d-4c7e-a8de-1322e2d993bc) database created.
        
      -  3.  Name the Database beer_factory_db and utf8mb4_general_c
## 1.Introduction
# 1.1.Overview of the Beer Factory Project:
  The Beer Factory provides a database solution that not only stores basic beer information such as names, alcohol levels, 
  descriptions, and country of origin but also tracks important business metrics like the stock quantity and price of each
  beer.
  The database integrates with a user-friendly web front end built with HTML and styled to give a unique presentation of 
  each beer.

## 2.Guide to Install 
# 1. Download & Install AMPPS on your Windows machine from AMPPS official website by following the installation steps.
*Note: First run of the AMPPS might take little time as it is setting up environment for you.
# 2. After installation Open AMPPS to start Apache and MySQL servers (turn both ON)
Example:
![image](https://github.com/user-attachments/assets/054dc797-39f3-4073-af3c-c1caf89db32b)

## 3.Step-by-Step Guide to Build the Beer Factory Project
    -create new database
    -create new table for that database
    -insert entries into the table created
    
# 3.1.Setting Up the Database:
      -  1.  To Access phpMyAdmin to manage databases, visit url https://localhost/phpmyadmin/:
  .![image](https://github.com/user-attachments/assets/54e01802-8b4e-4a6d-9584-7aabdf739431)
  
      -  2.  To Create New Database(2 ways): 1.Click New on the left sidebar. 2.Click on Databases tab on the top of the page navbar(both give same result):
  .![image](https://github.com/user-attachments/assets/38b7a60b-42b1-432c-b3f0-9fb93008deb9)
  i after that click on Create button.
  Name the Database beer_factory_db and utf8mb4_general_ci after that click on Create button. ![image](https://github.com/user-attachments/assets/4a765ade-3271-4d52-819c-08ceabfaf8fd)   
        After pressing Create button: ![image](https://github.com/user-attachments/assets/c3bd42f9-9f8d-4c7e-a8de-1322e2d993bc) database created.
        

# 3.1.Setting Up the Database:
  1.  To Access phpMyAdmin to manage databases, visit url https://localhost/phpmyadmin/ .![image](https://github.com/user-attachments/assets/54e01802-8b4e-4a6d-9584-7aabdf739431)
  2.  To Create New Database(2 ways): 1.Click New on the left sidebar. 2.Click on Databases tab on the top of the page navbar(both give same result).![image](https://github.com/user-attachments/assets/38b7a60b-42b1-432c-b3f0-9fb93008deb9)
  3.  Name the Database beer_factory_db and utf8mb4_general_ci after that click on Create button. ![image](https://github.com/user-attachments/assets/4a765ade-3271-4d52-819c-08ceabfaf8fd)   
      After pressing Create button: ![image](https://github.com/user-attachments/assets/c3bd42f9-9f8d-4c7e-a8de-1322e2d993bc) database created.
      
# 3.2.Creating table / tables for the database and inserting entries into the table created:
  -1.  To Create New Table Click on SQL tab on the top of the page navbar.![image](https://github.com/user-attachments/assets/bc8f8a0b-bc8e-4f02-bbf0-1be27ac2526a)
  2.  Now we will run the SQL query to create the table we want.                                                              
     -To Create new table named beers via SQL query we write: "CREATE TABLE `beers` ()                                        
     -Decide what type of data that will be stored inside each column creating a table.                                   
     -Data types and names: beer_id, beer_name, alcohol_level , description , beer_style , country_of_origin                                                             
      -                                                                    - beer_id will be of type int and PRIMARY KEY                                                                                 **PRIMARY KEY a field containing a value that uniquely identifies each record in a table.**
      **The primary key is unique and prevents entering duplicate records or a null value in that field.**
      - beer_name

Primary Key - a field containing a value that uniquely identifies each record in a table. The primary key is unique and prevents entering duplicate records or a null value in that field.
