[![License](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
# Ecommerce Back End

## Description
This is a sample Express back end application for an ecommerce store. This application allows a user to manage categories, tags, and products. There are GET (all/single), POST, PUT, and DELETE endpoints for categories, tags, and products. This code can be used as a starting point for an ecommerce site. Here is a [demo](https://drive.google.com/file/d/1aAP8td5YBxRJTwQbwPKUVVkns0ppOWQl/view).

## Table of Contents
1. [Installation](#installation)
2. [Usage](#usage)
3. [License](#license)
4. [Contributing](#contributing)
5. [Tests](#tests)
6. [Questions](#questions)

## Installation
You must install Node.JS (I used version 16.19.0) on your computer and run `npm i` to install the required modules. The program utilizes MySQL so that must be installed as well. You will need to create the `ecommerce_db` database by running `source <path/to/schema.sql>`. You can also run `npm run seed` if you'd like to import some sample data. The final step is to create a dotenv file to contain your MySQL credentials. The file should be named `.env` and contain the following database information: 
```
DB_NAME='staff_db'
DB_USER='your_username' 
DB_PW='your_pass'
``` 

You should then be ready to use the program.

## Usage
Run `npm start` to start the server. You can then use an API tool such as [Insomnia](https://insomnia.rest/) or [Postman](https://www.postman.com/) to make API calls. View the routes folder to see all of the available endpoints.

## License
This project is covered by the following license: [MIT License](https://opensource.org/licenses/MIT)

## Contributing
If you would like to contribute to the project, please contact me with one of the methods listed in the 'Questions' section.

## Tests
There are no tests for this application.

## Questions
Contact me at:
* GitHub - [dhoneck](https://github.com/dhoneck)
* Email - honeck_34@hotmail.com

