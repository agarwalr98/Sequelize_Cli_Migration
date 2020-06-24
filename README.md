## Sequelize-cli: Migration of databases

### About:
This repository contains basic steps to setup sequelize-cli for migrating your own database.

### Steps:
* Install the following packages using npm:
```npm install sequelize -g
   npm install sequelize-cli -g
   npm install dotenv path mysql                                                                        
```
**Note:** Install the database which you want to use in your project.
* Create a new directory in your project and navigate to it.
  ```mkdir src```
* Run ```sequelize init```.
  **Note:** If sequelize is not installed globally on your system then run, 
    ```node_modules/.bin/sequelize init```.                                 
* Create a ```.env``` file and change the variables according to your requirement.
* Move Config/config.js file from this repo to src/config.
* Copy .sequelizerc file into src directory and modify it.
* Now, you are ready to create tables in your db by using models.
* Follow the below mentioned sources.

### Sources/License:
1. https://sequelize.org/master/manual/migrations.html
2. https://sequelize.readthedocs.io/en/latest/docs/migrations/

