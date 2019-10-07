# MeanCourse App

- This project was created by me to investigate Angular framework and how it can work with node as i have always been a MERN Developer not a Mean Developer

# Structure and how to deploy the app

- This application is divided into 2 apps

  - A backend app written in Javascript using **NodeJS** and integrated with a remote **MongoDB** Database

    - To run the backend just write in the terminal `npm run start:server`

  - A Frontend app written in typescript using **Angular** version 8
    - To run the Frontend just write in the terminal `npm run start:server`

## Features applied in the Angular App

- Using Angular Material Design for decent a UI
- Applying both Reactive approach and Form approach in creating and validating form
- Using Angular Router for managing frontend routes
- Using Lazy Loading for the routes by making a route file for each module and just importing it in the app-route file
- Using Angular guard to prevent accessing Application routes when user is not authenticated
- Using Angular interceptor to add JWT TOKEN for each HTTP Request going from the App to the Server
- Using Angular interceptor for error handling
- Implementing Image upload to remote server and MIME-Verification for the image file before it is uploaded to the server

## Features applied in the NodeJS App

- Integration with Remote MongoDB
- Encrypting passwords using bycrypt
- Validation for each Route Access Using The `JWT` token Sent
- Validation for the uploaded images and saving it on the server
- Handling invalid route access
- Handling unauthorized route requests
- Handling inserting unique records in the users table in MongoDB using `mongoose-unique-validator`
- Handling pagination requests
- Handling CORS Error
