# challengeWispock
# CRUD User RESTful API

This RESTful API provides CRUD (Create, Read, Update, Delete) functionalities for managing users. It's a flexible and scalable solution for handling user information over HTTP.

## Features

- **CRUD Operations**: Allows creating, reading, updating, and deleting users.
- **Authentication and Authorization**: Implements authentication and authorization mechanisms to secure API routes.
- **Data Validation**: Performs data validation to ensure data integrity.
- **Documentation**: Clear and concise documentation on API usage.

## Technologies Used

- **Programming Language**: Typescript and Node.js.
- **Framework**: Express.js
- **Database**: MongoDB
- **Additional Tools**: Mongoose

## Installation

1. Clone this repository: `git clone https://github.com/Rodrigo0311/challengeWispock.git`
2. Install dependencies: `npm install`
3. Start the server: `npm start`

## Usage

1. **Create a User**: `POST /user`
   Payload: `{
    	"name": "Prueba",
    	"email": "prueba5@prueba.com",
    	"phone": "33310109944"
    }`
3. **Get All Users**: `GET /user`
4. **Get a User by ID**: `GET /user/:id`
5. **Update a User**: `PUT /user/:id`
   Payload: `{
    	"name": "Prueba",
    	"email": "prueba5@prueba.com",
    	"phone": "33310109944"
    }`
7. **Delete a User**: `DELETE /user/:id`

