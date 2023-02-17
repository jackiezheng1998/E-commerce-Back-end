# E-commerce-Back-end

# User Story
AS A manager at an internet retail company
I WANT a back end for my e-commerce website that uses the latest technologies
SO THAT my company can compete with other e-commerce companies

# Acceptance Criteria
GIVEN a functional Express.js API
WHEN I add my database name, MySQL username, and MySQL password to an environment variable file
THEN I am able to connect to a database using Sequelize
WHEN I enter schema and seed commands
THEN a development database is created and is seeded with test data
WHEN I enter the command to invoke the application
THEN my server is started and the Sequelize models are synced to the MySQL database
WHEN I open API GET routes in Insomnia Core for categories, products, or tags
THEN the data for each of these routes is displayed in a formatted JSON
WHEN I test API POST, PUT, and DELETE routes in Insomnia Core
THEN I am able to successfully create, update, and delete data in my database

# Description
This is a backend application that has been developed using NODE.js, Sequelize, Express, and dotenv to provide support for the front-end of an e-commerce website. Its primary function is to help users manage data under three categories: Category, Tag, and Product. These categories are interdependent and can be searched easily using predefined standards. The application has been built using object-relational mapping and command line interface (CLI) to perform various methods of data manipulation, storage, and retrieval via HTTP methods using a RESTful API. To interact with the MySQL database, the application employs Express.js API and Sequelize. Its aim is to create an efficient and user-friendly backend for an online shop.

# Installation 
npm install command will install javascript dependencies
npm i
npm run seeds
npm start

# Mock Up
![13-orm-homework-demo-01](https://user-images.githubusercontent.com/118042037/219538534-a5cfbe38-f379-41da-abba-5a2edcf5dbbd.gif)
![13-orm-homework-demo-02](https://user-images.githubusercontent.com/118042037/219538546-23eb9bcd-cf5f-4a15-933d-65f722a930c1.gif)
![13-orm-homework-demo-03](https://user-images.githubusercontent.com/118042037/219538571-79ca5068-fc8d-4223-961a-7f9e8032677d.gif)




