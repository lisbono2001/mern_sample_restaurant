# Restaurant Reviews

This is a project about CRUD (create read update delete) about restaurant reviewing using MERN stack (mongo express react node) and MongoDB Realm.

## Description

This is a simple web-application that can manage product that invole, creating, editing and deleting. Using NodeJS with React and Express while database is using MongoDB and deploy both client side and server side at [MongoDB Realm](https://www.mongodb.com/realm).

## Deployment

[deployed server](https://restaurant-reviews-mixns.mongodbstitch.com/)

## Prerequisites

[nodejs](https://nodejs.org/en/)
[mongodb](https://www.mongodb.com/)

## Getting start

#### Start Frontend Server

In repository directory

```
yarn
yarn start
```

#### Start Backend Server

In backend file directory create .env file inorder to run the server using these configuration settings

```
RESTREVIEWS_DB_URI = mongodb+srv://admin:admin@cluster0.mqxq0.mongodb.net/sample_restaurants?retryWrites=true&w=majority
RESTREVIEWS_NS = sample_restaurants
PORT = 5000
```

Start the server

```
yarn
yarn index.js
```
