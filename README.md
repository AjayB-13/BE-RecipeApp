# Recipes CRUD App

## Description
A simple CRUD app for managing recipes using Node.js, Express, and MongoDB.

## API Postman Documentation URL -
https://documenter.getpostman.com/view/47048371/2sB3B8tDnn

## Features
- Create, Read, Update, Delete recipes
- MongoDB + Mongoose integration
- MVC Architecture
- API tested with Postman

## Installation
1. Clone repo
2. Run `npm install`
3. Add `.env` file
4. Run server: `npm run dev`

## API Endpoints
| Method | Endpoint         | Description        |
|--------|------------------|--------------------|
| POST   | /api/recipes     | Create a recipe    |
| GET    | /api/recipes     | Get all recipes    |
| GET    | /api/recipes/:id | Get recipe by ID   |
| PUT    | /api/recipes/:id | Update recipe by ID|
| DELETE | /api/recipes/:id | Delete recipe by ID|

---
