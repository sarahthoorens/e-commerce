# E-commerce Back-End Build
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)


  **Completion Date:**  11/04/22 
  
  [**WALK-THROUGH CAN BE FOUND HERE**](https://watch.screencastify.com/v/o3AYqtaDVb3dkqL39i68)<br>
  
  **Technologies used:**  Node.js, JavaScript, Sequelize, Express.js API, MySql<br>
  **Project goal:** Build the back end for an e-commerce site by modifying starter code. <br>


  ## Table of Contents
  1. [Project Description](#Description)
  2. [Installation](#Installation)
  3. [Contribution Guidelines](#Contributing)
  4. [Challenges Encounted](#Challenges)
  5. [Tests](#Tests)
  6. [License](#License)
  <br>
  
  ## Description

  The instructions for this project were to build the back-end of an e-commerce site using Sequelize ORM models and MySQL to effectively interact with the inventory data after seeding a database. Server tests using Insomnia were required to confirm GET, POST, and DELETE routes were correctly coded to interact with the product, category and tag models. 

  ![Insomnia demo screenshot at products list](/Develop/assets/insomnia.png)

   ## User Story

   ```md
   AS A manager at an internet retail company
   I WANT a back end for my e-commerce website that uses the latest technologies
   SO THAT my company can compete with other e-commerce companies
   ```

   ## Acceptance Criteria

   ```md
   GIVEN a functional Express.js API
   WHEN I add my database name, MySQL username, and MySQL password to an environment variable file
   THEN I am able to connect to a database using Sequelize
   WHEN I enter schema and seed commands
   THEN a development database is created and is seeded with test data
   WHEN I enter the command to invoke the application
   THEN my server is started and the Sequelize models are synced to the MySQL database
   WHEN I open API GET routes in Insomnia for categories, products, or tags
   THEN the data for each of these routes is displayed in a formatted JSON
   WHEN I test API POST, PUT, and DELETE routes in Insomnia
   THEN I am able to successfully create, update, and delete data in my database
   ```

  ## Installation

  To implement this program, you'll need to create the e-commerce database via MySQL, seed the data and connect server to the localhost. You'll run your routes through Insomnia to test functionality.

  ## Contributing

  Contributions are welcome. My contact information is below.
 
  ## Challenges
 
  This was a very straight-forward project that, although not entirely difficult, relied heavily on new-to-me syntax, which perhaps was the biggest challenge. I also spent far too long investigating a [known issue](https://github.com/sequelize/sequelize/issues/4708) that required adjusting category name and product name to 'allowNull=true' values in order for tests to run appropriately. 

  ## Tests

  No tests were written for this program.

  ## License

  Click the badge to learn more about the license used for this project.
  <br>[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

  ## Questions?

  Find me on GitHub at: https://github.com/sarahthoorens

  You can also send any questions about this project to: s.thoorens@gmail.com



