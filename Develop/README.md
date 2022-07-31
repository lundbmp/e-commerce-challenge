# E-Commerce Challenge
## Description
This project shows the capabilities of ORM (object relational mapping). By creating models and using the built in functionality of them, we can map data to a database without making queries.

## How to Install
After downloading the project and navigating to the project directory type `npm i` and the proper dependencies will be installed. In the .env file add your mysql username and password to the appropiate places. Start up MySQL to run the `schema.sql` in the `db` folder. Seed the project by running `npm run seed` in the command prompt. Then `npm start` to begin the program.

## How to Use
Once the program is running you can access the API by accessing any of these routes:
`http://localhost:3001/api/tags/` => `GET` `POST`
`http://localhost:3001/api/tags/:id` => `GET` `PUT` `DEL`
`http://localhost:3001/api/categories/` => `GET` `POST`
`http://localhost:3001/api/categories/:id` => `GET` `PUT` `DEL`
`http://localhost:3001/api/products/` => `GET` `POST`
`http://localhost:3001/api/products/:id` => `GET` `PUT` `DEL`
They can be accessed via the browser, insomia, postman, or similar programs.

## Credits
The starter code was from Xandromus and was completed by Michael Lundberg
