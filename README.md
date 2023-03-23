# Student-Enrollment-Form
## Description 
This is a web based html form for student enrollment using JsonPowerDB as Database 
JsonPowerDB is used to perform CRUD operation 

# Table of Contents
* [Description](#description)
* [Benefits of Using JsonPowerDB](#benefits-of-using-jsonpowerdb)
* [Tech Stack Used](#tech-stack-used)
* [Release History](#release-history)
* [Illustrations](#illustrations)
* [How To Use](how-to-use)
* [Installation](#installation)
* [Sources](#sources)


# Benefits of using JsonPowerDB
* Simple to use , real time database
* Simplest way to retrieve data in a JSON format.
* Backends code is not required for database 
* No need for defining schema 
* Querying the database is easy there is no need  of knowledge of SQL commands
* It helps developers in faster coding, in-turn reduces development cost

# TECH STACK USED
* HTML
* CSS
* JAVASCRIPT 
* JsonPowerDB ( As Database)

## Release History
#### v0.0.0 (24/03/2023)
##### Initialization:
- [#1] Added basic designs of all planned HTML pages
---
#### v0.1.0 (24/03/2023)
##### Enhancements:
- [#2] Designed all HTML pages
- [#3] Added JS and connected pages to JsonPowerDB
- [#4] Tested all pages
---
#### v0.1.1 (24/03/2023)
##### Enhancements:
- [#5] Added a README.md file
- [#6] Few CSS changes

# Web APP Screenshots:
<img src="/images/Screenshot (583).png">
<img src="./images/Screenshot (582).png">

# Illustrations:
* **UPDATE** : when student roll number is already present in database then student information is fetched from database and filled in respective feild then user can UPDATE student information 
* **SAVE** : If student roll number is not existed in database then we can fill other field and save in database
* **Clear** : By this we can clear all field of form and with this except first field (roll-no) other field are disabled until user enter any roll number
* **Alert** : This website uses disposable Alter prompt using bootstrap

# HOW TO USE

* **Initially**
<img src="./images/Screenshot (583).png">

We need to enter a roll number 

If roll number is not valid 

<img src="./images/Screenshot (580).png">

If roll number is valid and then we can enter details of student

<img src="./images/Screenshot (584).png">
  
* **Updation of student details**
  In order to update student details input roll number, and then we can update the student data
  
  <img src="./images/Screenshot (581).png">

* **Adding new student data**

  Enter new roll number and then all other fields are enabled and then after filling student information we can save this data into database only if input is valid
  
  <img src="./images/Screenshot (579).png">
    
  
  # Installation
  
  Make a folder in your system and clone the project using git bash then open the project in Visual Studio Code or any IDE you prefer.
  ##### Clone the project 
  ```
    https://github.com/SwarupKMondal/Student-Enrollment-Form-Web-App.git
  ```
  After cloning 
  
  Move to **public_html** and then **script** folder and in **script.js** file replace the **connectionToken** by with your Connection Token
  
  # Sources
  * Introduction to JsonPowerDB - V2.0 course  on https://careers.login2explore.com/
  * [Bootstrap](https://getbootstrap.com/docs/5.0/getting-started/introduction/) 
  
  

  --------------------
## Hope You Like the Project ❤️❤️❤️

