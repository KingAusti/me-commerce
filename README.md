# me-commerce

## User Story

AS A manager at an internet retail company<br>
I WANT a back end for my e-commerce website that uses the latest technologies<br>
SO THAT my company can compete with other e-commerce companies<br>

---
* [Installation](#installation)

* [About](#about)

* [Demo](#demo)

* [Author](#author)
---
### Installation
1. Clone repository using 'git clone"
2. Install necessary dependencies, run the following command: <br> 'npm install'
3. Create Table using mysql2(login to my mysql, run 'SOURCE db/schema.sql')
3. Seed Table('npm run seed')
3. To run application 'npm run start' in the command line


---
### About
This a project was built using <br>
* Node.js
* Inquirer
* MySQL2
* javaScript
* dotenv

---

### DEMO 
![Walkthrough](./public/ecomm_walkthrough_1.gif)<br>
[Full Video Walkthrough](https://drive.google.com/file/d/11guT-MjUUE8StT3hyvzolyTFL6MRNicT/view?usp=sharing)

---

## AUTHOR

### [KingAusti](https://github.com/KingAusti)
---
## Acceptance Criteria

GIVEN a functional Express.js API<br>
WHEN I add my database name, MySQL username, and MySQL password to an environment variable file<br>
THEN I am able to connect to a database using Sequelize<br>
WHEN I enter schema and seed commands<br>
THEN a development database is created and is seeded with test data<br>
WHEN I enter the command to invoke the application<br>
THEN my server is started and the Sequelize models are synced to the MySQL database<br>
WHEN I open API GET routes in Insomnia for categories, products, or tags<br>
THEN the data for each of these routes is displayed in a formatted JSON<br>
WHEN I test API POST, PUT, and DELETE routes in Insomnia<br>
THEN I am able to successfully create, update, and delete data in my database<br>