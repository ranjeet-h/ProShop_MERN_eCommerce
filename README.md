# ProShop eCommerce Platform

> eCommerce platform built with the MERN stack & Redux.

This is a MERN stack eCommerce app, Build with React,NodeJs,ExpressJs,MongoDB. Used React-Bootstrap for styling. Also used BootsWatch as free  React-Bootstrap Themes 


## Overview

### Screenshot

![](./screenshot.png)
## Features

- Full featured shopping cart
- Product reviews and ratings
- Top products carousel
- Product pagination
- Product search feature
- User profile with orders
- Admin product management
- Admin user management
- Admin Order details page
- Mark orders as delivered option
- Checkout process (shipping, payment method, etc)
- PayPal / credit card integration
- Database seeder (products & users)



## Usage

### ES Modules in Node

We us ECMAScript Modules in the backend in this project. Be sure to have at least Node v14.6+ or you will need to add the "--experimental-modules" flag.

Also, when importing a file (not a package), be sure to add .js at the end or you will get a "module not found" error

You can also install and setup Babel if you would like

### Env Variables

Create a .env file in then root and add the following

```
NODE_ENV = development
PORT = 5000
MONGO_URI = your mongodb uri
JWT_SECRET = 'abc123'
PAYPAL_CLIENT_ID = your paypal client id
```

### Install Dependencies (frontend & backend)

```
npm install
cd frontend
npm install
```

### Run

```
# Run frontend (:3000) & backend (:5000)
npm run dev

# Run backend only
npm run server
```

## Build & Deploy

```
# Create frontend prod build
cd frontend
npm run build
```

There is a Heroku postbuild script, so if you push to Heroku, no need to build manually for deployment to Heroku

### Seed Database

You can use the following commands to seed the database with some sample users and products as well as destroy all data

```
# Import data
npm run data:import

# Destroy data
npm run data:destroy
```

```
Sample User Logins

admin@example.com (Admin)
123456

john@example.com (Customer)
123456

jane@example.com (Customer)
123456
```


## My process

### Built with

- Semantic HTML5 markup
- React-Bootstrap CSS and SCSS custom properties
- Mobile-first workflow
-[BootsWatch](https://bootswatch.com/) - Bootstrap Free Themes
- [React](https://reactjs.org/) - JS library

## Author

- Website - [Reanjeet Harishchandre (HR Developer) (https://modest-jones-78fd0c.netlify.app/)](https://www.your-site.com)

**Note: Delete this note and add/remove/edit lines above based on what links you'd like to share.**

## Acknowledgments

HR Developers
