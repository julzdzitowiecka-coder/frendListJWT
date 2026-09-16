# Express.js Authentication API

Simple authentication API built with Node.js, Express.js, JWT and sessions.

## Features
* User registration
* User login
* JWT authentication
* Session management
* Protected /friends routes

## Technologies
* Node.js
* Express.js
* JSON Web Token
* Express Session

## Installation
npm install

## Run
node app.js

## Server runs on:
http://localhost:5000

## API
### Register
POST /register
{
  "username": "john",
  "password": "123456"
}
### Login
POST /login
{
  "username": "john",
  "password": "123456"
}
### Friends
Protected endpoint:
GET /friends

Authentication is required.
