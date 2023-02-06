# ORM Ecommerce backend 

## Description
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

I learned a lot about sequalize with this project and was able to better grasp constructing and connecting tables with it.

## Installation

Once code is downloaded, run npm install to receive dependencies
Next open MySQL shell and log in, run the schema via SOURCE db/schema.sql, quit the shell.
To seed the data type npm run seed in the command-line.
Finally to launch the server, type npm start in the command line.

## Usage

Once the server is launched it can be found on port 3001. Using Insomnia one can access “api/products”, “api/categories”, and “api/tags”. Within these categories you can GET POST PUT and DELETE.

https://drive.google.com/file/d/1hnvUyP7IK1el18X9ejjz5jl8QND7Utab/view


## Credits
Original code from: https://github.com/coding-boot-camp/fantastic-umbrella
Stackoverflow
JsonLint
PedroTech on youtube


## License

Copyright 2023 Madeline Gillis

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
