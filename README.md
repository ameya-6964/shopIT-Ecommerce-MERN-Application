# ShopIT E-commerce Project

> shopIT-Ecommerce-MERN-Application is a full-stack e-commerce application built with the MERN stack (MongoDB, Express, React, and Node.js). The application features user registration and login, product listing and search, cart and checkout, Stripe payment integration, and user reviews. The project is well-organized and documented, and it would be a good starting point for anyone who wants to learn how to build an e-commerce application with the MERN stack.

# Description

> This project is a full-stack e-commerce application built with the MERN stack. The application features the following:

- User registration and login
- Product listing and search
- Cart and checkout
- Stripe payment integration
- User reviews

> Tech Stack

- MongoDB
- Express
- React
- Node.js
- Stripe

### Install MongoDB Community Server

```
https://www.mongodb.com/try/download/community
```

### Install MongoDB Compass

```
https://downloads.mongodb.com/compass/mongodb-compass-1.38.0-win32-x64.exe
```

### Env Variables

Rename configFiles.env to config.env in backend/config folder

Add your config variables values in the config.env file in backend/config folder

- PORT = 4000
- NODE_ENV = DEVELOPMENT
- DB_LOCAL_URI = mongodb://127.0.0.1:27017/shopit
- DB_URI = Add This When You Host Your Database Online
- FRONTEND_URL = "http://localhost:3000"

* JWT_SECRET = SDFDFSHDFHDUISHHUDFHUISHFIUSHDFHFDHIUSDH3432H4J23HE2HUH2S (Any Random Value)
* JWT_EXPIRES_TIME = 7d (Any Random Value)
* COOKIE_EXPIRES_TIME = 7 (Any Random Value)

### For Cloudinary Config

- Create Account On https://cloudinary.com

- ![Alt text](<cloudinary API.png>)

- CLOUDINARY_CLOUD_NAME =
- CLOUDINARY_API_KEY =
- CLOUDINARY_API_SECRET =

### For Stripe Config

- Create Account On https://stripe.com/en-in

- ![Alt text](<Stripe API.png>)

- STRIPE_SECRET_KEY =
- STRIPE_API_KEY =

### For Mailtrap Config

- Create Account On https://mailtrap.io/

- ![Alt text](<mailtrap API.png>)

- SMTP_HOST =
- SMTP_PORT =
- SMTP_EMAIL =
- SMTP_PASSWORD =
- SMTP_FROM_EMAIL = noreply@shopit.com
- SMTP_FROM_NAME = shopit

### Install Dependencies (Backend)

```
cd backend
npm i --force
```

### Install Dependencies (Frontend)

```
cd frontend
npm i --force
```

### Seed Database

Use the following commeand to put some dummy products in that database.
Run it in the root folder.

```
npm run seeder
```
