# Louis-Module-13-Object-Relational-Mapping
## Description
I've been tasked with adding code for a back end for my e-commerce website that uses the latest technologies
so that it can compete with other e-commerce companies
I am able to connect to a database using Sequelize when I add my database name, PostgreSQL username, and PostgreSQL password to an environment variable file.
A development database is created and is seeded with test data when I enter schema and seed commands.
My server is started and the Sequelize models are synced to the PostgreSQL database when I enter the command to invoke the application
The data for each of these routes is displayed in a formatted JSON when I open API GET routes in Insomnia Core for categories, products, or tags.
I am able to successfully create, update, and delete data in my database when I test API POST, PUT, and DELETE routes in Insomnia Core.
Lastly, I left the code better than I found it.

## What's Included
* config Folder
    * connection.js
* db Folder
    * connection.js
* models Folder
    * Category.js
    * index.js
    * Product.js
    * ProductTag.js
    * Tag.js
* routes Folder
    * api Folder
        * category-routes.js
        * index.js
        * product-routes.js
        * tag-routes.js
* seeds Folder
    * category-seeds.js
    * index.js
    * product-seeds.js
    * porduct-tag-seeds.js
    * tag-seeds.js
* package.json
* .gitignore
* README.md
* server.js
  
## How to setup
  * First gitclone the application to your machine.
  * Next open the application in vscode. 
  * Then open a terminal in vscode.
  * Enter in the following npm packages
        * npm i pg
        * npm i sequelize
        * npm i dotenv
  * Open Postgresql and start it up.
  * Enter into the terminal "psql -U postgres", and enter your password to connect to the sever.
  * Then enter "CREATE DATABASE ecommerce_db"
  * After creating a database create an .env File.
  * With your .env enter in your database name, username, and password.
  * Enter in npm run seed.
  * Open Insomnia
  * In Insomina create a Folder for Product, Category, and Tags.
  * Then create a Put, Del, Create, Get One or Pural, and Get All or Id.
  * Then create the json code for each of the files.
  * Finally after that you should be able to update, delete, create, get one or more Insomnia.


## Screenshot
![Screenshot 2024-07-01 183527](https://github.com/Dark-N-Oak/Louis-Module-13-Object-Relational-Mapping/assets/163933013/bb290191-0508-4f56-80d7-ef4fac5226cf)

## Video
https://drive.google.com/file/d/10O9z1muHs7Z33yKGM0fyw5jy76iqQ1CK/view?usp=drive_link
