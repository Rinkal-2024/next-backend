# E-commerce Project Setup Guide

## Backend Setup
Create a .env file in the root of your backend directory and add the following environment variables:

```
MONGODB_URI=
PORT=
receiving_email=
EMAIL_PASSWORD=
SHIPPING_FEE=
STRIPE_SECRET_KEY=
CLOUDINARY_SECRET_KEY=
CLOUDINARY_CLOUD_NAME=
CURRENCY=
JWT_SECRET=
```

Installing Dependencies
```npm install```

Running the Server
```bash
npm start
```


## Frontend Setup
Create a .env.development and .env.production files with the same variables in the root of your frontend directory and add the following environment variables:
``` .env
BASE_URL= // Base URL for the backend API
STRIPE_PUBLIC_KEY=
STRIPE_SECRET_KEY=
CLOUDINARY_CLOUD_NAME=
CURRENCY=USD
SHIPPING_FEE=
JWT_SECRET=
```

Installing Dependencies
```npm install```

Running the Application
```npm run dev```
