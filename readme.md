# Node API
A Node JS API which saves 'Post' data to a Mongo DB instance. 
Implemented from the tutorial: https://www.youtube.com/watch?v=vjf774RKrLc

###Endpoints

These endpoints are supported:

1. `GET /`  - displays a message indicating that it is the home page.
2. `GET /posts`  - displays all posts records stored in the MongoDB.
3. `GET /posts/{PostID}`  - gets the post records with the specific PostID.
4. `POST /posts`  - creates a new Posts and saves it in the MongoDB.
5. `DELETE /posts/{PostID}`  -  deletes the post record with the specific PostID.
5. `PATCH /posts/{PostID}`  -  updates the title of the post record with the specific PostID.