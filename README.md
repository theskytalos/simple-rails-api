# Simple Rails API

Just a (very) simple articles RESTful API made only for learning purposes.

## Usage

This app uses SQLite, therefore, make sure you have it installed in your envronment.
The "localhost" is assuming that your are hosting this API on your own machine.

### Add a user
**Request**

`POST http://localhost:3000/api/v1/articles`

**Body**
`{
  "title": "The article title", 
  "body": "The article body"
}`

### Edit a user
**Request**

`PUT http://localhost:3000/api/v1/articles/:id`

**Body**

`{
  "title": "The article title",
  "body": "The article body"
}`

### Delete a user
**Request**

`DELETE http://localhost:3000/api/v1/articles/:id`

### Show all users
**Request**

`GET http://localhost:3000/api/v1/articles`

### Show specific user
**Request**

`GET http://localhost:3000/api/v1/articles/:id`
