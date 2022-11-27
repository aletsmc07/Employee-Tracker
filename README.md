# Employee Tracker
## _Database for your company._

[![Build Status](https://travis-ci.org/joemccann/dillinger.svg?branch=master)](https://travis-ci.org/joemccann/dillinger)

Command line app that helps you to control of your employees.
- Register or Delete employees.
- See their basic info and change properties.

## Content
- [Features](#Features)
- [Tech](#Tech)
- [Installation](#Installation)
- [Links](#Links)
- [Screenshots](#Screenshots)
- [License](#License)

## Features

- Search by department, roles or employees; also you can search employees by department or manager.
- Add a department, new role or an employee.
- Update an employee role or manager.
- Delete a complete department, role or an employee.

[Content](#Content)

## Tech

This app was made with:

- [HTML](https://developer.mozilla.org/es/docs/Web/HTML)
- [Node JS](https://nodejs.org/en/)
- [Express JS](https://expressjs.com/)
- [MySQL](https://www.mysql.com/)

[Content](#Content)

## Installation

Clone the repository on your PC, open it on Visual Studio Code or other source code editor of your choice and follow the next steps:
- Open the terminal and install all dependencies (Inquierer) :
```
    npm install inquirer
```

- Create an .env file and change the sata with your own info if applicable:
```
    DB_HOST= localhost
    DB_PORT= 3306
    DB_USER= yourUser
    DB_PASS= yourPassword
```

- To create and run database start MySQL:
```
    #work on MySQL
        mysql -u root -p
        
    # to create the DB schema
        db/SOURCE schema.sql
    
    # to add some data (optional; this example contains data to show that the app works)
        db/SOURCE seeds.sql
```

- To start the app (maybe you will need to open other commandline without close or stop MySQL and type the next command:
```
    node index.js
```

Please, install Node JS (link of the specified in Tech section) before run the commands.

[Content](#Content)

## Links

- [Github repository](https://github.com/aletsmc07/Employee-Tracker)
- No deployed app link, run it in terminal.

[Content](#Content)

## Screenshots
- Running DB:
![image](https://user-images.githubusercontent.com/107447818/204120631-0a070d0a-33fd-4dd1-a2ad-792af6547b40.png)

- Starting app (running mysql and node js in different terminals):
![image](https://user-images.githubusercontent.com/107447818/204120758-88a70a7a-3aa7-45e4-9c72-939ad54a4715.png)

- View menu:
![image](https://user-images.githubusercontent.com/107447818/204120786-984f6c7c-671b-4814-af3d-ddf400364c17.png)

- Table of all employees:
![image](https://user-images.githubusercontent.com/107447818/204120842-9ed5e98b-70a4-4fe0-a764-4d2ab13b464f.png)

- Adding a new employee:
![image](https://user-images.githubusercontent.com/107447818/204120854-c46bb043-b9df-4bcd-9c49-2cedecfe3c27.png)

![image](https://user-images.githubusercontent.com/107447818/204120894-6604534c-9ce7-4c97-8f25-89b4d781b7f5.png)

- New employee added succesfully to DB:
![image](https://user-images.githubusercontent.com/107447818/204120929-7ad6cb22-235c-4aee-ab6a-cbf819309330.png)

- Updated role of an specific employee:
![image](https://user-images.githubusercontent.com/107447818/204120990-c9c7a321-299e-4b0f-8868-5a7c62f72418.png)

- Deleting an employee:
![image](https://user-images.githubusercontent.com/107447818/204121009-93868b18-37e5-4db1-9c54-c9a66c6a8f10.png)

[Content](#Content)

## License

MIT

**Educational Software**

[Content](#Content)
