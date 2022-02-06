# E-Commerce database
  ![License](https://img.shields.io/badge/License-MIT-red.svg)
  
  ## <a id="DESCRIPTION"> DESCRIPTION</a>
This project was built to demonstarte how I could repair already given code into a working database hosted on a server(express) and have it be manageable using url requests. 

  ## Project Contents
  - [DESCRIPTION](#DESCRIPTION)  
  - [SCREENSHOT](#SCREENSHOT)  
  - [INSTALLATION](#INSTALLATION)  
  - [USAGE](#USAGE)  
  - [CONTRIBUTING](#CONTRIBUTING)  
  - [QUESTIONS](#QUESTIONS)
  - [TESTS](#TESTS)
  - [LICENSE](#LICENSE)  
  
  ## <a id="SCREENSHOT"> SCREENSHOT</a>
  ![screenshot](https://i.gyazo.com/18f6301b11b0c234fd4f03b0479afbd7.png)

  ## <a id="INSTALLATION"> INSTALLATION</a>
  NPM I 

  ## <a id="USAGE"> USAGE</a>
To use and or test the application, the user needs to create a .env file that has a DB_NAME, DB_PW and DB_USER to allow the SQL database to be sourced and seeded. The user will then need to source the schema through the DB folder either through workbench or SQL CLI. Once that file is seeded the user then needs to run the index.js file inside of the seeds folder. Then launching the express server through either "RUN NPM WATCH" or simply "node server.js" will start the server with the relative database loaded. The user can then navigate over to their application of choice that has the abilites to monitor requests to the server such as Postman/Hoppscotch or as I recommend in this case using insomnia as the server will be ran at a local port as local host. the user will then need to set up the relative requests they wish to make, the user can make two get requests one by general url paths like /tags /products /categories but they can also use /<:id>
in these paths for more specified results they can also use deletes/gets and posts for updating and creating more entries in to this database. 
  
  ## <a id="QUESTIONS"> QUESTIONS</a>
  Any questions you can reach me at EoinHarky@gmail.com or my github page https://github.com/HarkyDev

  ## <a id="TESTS"> TESTS </a>
  npm test

  ## <a id="CONTRIBUTING"> CONTRIBUTING</a>
  Users who contributed to this project:
 -  https://github.com/HarkyDev
 -  




  ## <a id="LICENSE"> LICENSE</a>
  
  MIT
  https://opensource.org/licenses/MIT
  
