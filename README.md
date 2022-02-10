# Design Assumptions

This document shall describe all fundamental ideas and decisions on which this project will be made.

### This document shall contain:

1. [Basic description of this project](#Basic-description-of-this-project)
2. [Tech Stack](#Tech-Stack)

# Basic description of this project

The result of completion of work on described project should be an auction website similar in functionality to [ebay](https://ebay.com) and [allegro](https://allegro.pl). All users should be able to buy, sell, search for and watch products listed on this website by other users. All listings should be divided into categories and subcategories and those should in an accurate way describe contained in them products. One listing should be contained in only one category and subcategory (which is related to the category). Users can order products from multiple sellers (which are also users of this software in meaning of the architecture) to multiple saved locations/addresses. Users can save listings to a watchlist in case they want to come back to them later.

# Tech Stack

Listed bellow technologies shall help in solving a problem of creating such project.

**NOTE: This list may change in case when listed technologies fail to deliver satisfactory solution to the problem posed or feature set of this project changes resulting in need to modify a tech stack to deliver this project**

How to read this section
- Division in this project
    - Technology 1
    - Technology 2
    - ...

### Sugested technologies:

- Backend
    - Node.JS - Runtime for created scripts
    - Nest.JS with TypeScript - backend backbone
    - Stripe - Payment Processing
    - SendGrid - email delivery service
    - Typeorm - database connection
    - Bcrypt - password hashing
    - JSON web token - auth
- Frontend
    - React with TypeScript
    - Next.JS
    - Redux - Global state managment
    - Yup - form validation
    - Formic - form validation
    - TailwindCSS - styling
- Database engine(s)
    - MySQL - Main database engine
- Enviroment
    - NGINX - web server
    - Ubuntu 20.04 LTS