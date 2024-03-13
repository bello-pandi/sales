## **SalesBill -Invoicing Solution:**

A web application for small business owners and freelancers needing a simple and professional invoicing solution.
## Core features

- User authentication (jwt) for security

- Storing / Viewing products & customers and linking them

- PDF invoice generation, & printing, Managing already generated ones

## Languages and Tools

Front-end- ExpressJS / HTML5, jQuery 3, Bootstrap 3, CSS

Backend- NodeJS/ Express

Database - MySQL 8

> Libraries Used-

**Font Awesome (icon)** - `https://fontawesome.com/v4.7.0/`

**Datatable** - `https://datatables.net/`

--

## Starting the project
Create a schema in your MySQL instance called `sales`
Create tables from `sqlQueries.sql` in the same order as provided in file.

#### Setting up Config
In default.json in config folder in api, change the values of `dbname` to `sales` and `host`, `user` and `password` to your corresponding database hostname, usermane and password

In .env in app, replace the values of PORT, API_URL and API_PORT with Server Port, API server hostname, API server port number. 
`dbname` to `sales` and `host`, `user` and `password` to your corresponding database hostname, usermane and password

#### Testing on Dev Environment
To start the server, goto api directory in terminal and run `npm install` and `npm run dev`

To start the front-end, goto app directory in terminal and run `npm install` and `npm run dev`
#   s a l e s  
 