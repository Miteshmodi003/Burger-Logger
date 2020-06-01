# Eat-the-Burger!
This assignment was created to show a burger logger with MySQL, Node, Express, Handlebars and a homemade ORM. I also followed the MVC (Model-View-Controller) design pattern. I used Node and MySQL to query and route data in my app, and Handlebars to generate my HTML.

To see the app in action, click the link below:

https://quiet-scrubland-49398.herokuapp.com/

## How to Use:
The user places their order at the bottom of the page, where there is a form to input their preferred burger. After clicking the "Order!" button, their burger will populate on the left column under "Enjoy your meal!" as well as a "Eat it!" button at the bottom. When the user decides to eat their burger, the burger will then be displayed on the right column under "Previous Orders".

## Directory structure

All the recommended files and directories from the steps above should look like the following structure:

```
.
├── config
│   ├── connection.js
│   └── orm.js
│ 
├── controllers
│   └── burgers_controller.js
│
├── db
│   ├── schema.sql
│   └── seeds.sql
│
├── models
│   └── burger.js
│ 
├── node_modules
│ 
├── package.json
│
├── public
│   └── assets
│       ├── css
│       │   └── burger_style.css
│       ├── img
        └── js
│           └── burgers.js
│   
│
├── server.js
│
└── views
    ├── index.handlebars
    ├── partials
    |   └── burger-block.handlebars
    └── layouts
        └── main.handlebars
```

## Technologies Used:
* Express
* Node
* MySQL
* Handlebars.js
* HTML/CSS
* JavaScript/jQuery
* API calls/routing
* Heroku
