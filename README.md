# BLOGPOST Management API

This repository contains a REST API for managing blog posts, implemented in `post.js`.

## Prerequisites

- Node.js (v14 or later)
- npm (v6 or later)

## Setup

1. Clone this repository:
   git clone https://github.com/rohanindaragi/BLOGPOST.git
   cd BLOGPOST

2. Install dependencies:
    npm i

3. Start the server:
    nodemon post.js

## API Endpoints
Method	Endpoint	Description
GET	/api/posts	Retrieves all posts
GET	/api/posts/:id	Retrieves a specific post by ID
POST	/api/posts	Creates a new post
PUT	/api/posts/:id	Updates an existing post
DELETE	/api/posts/:id	Deletes a post

## Contributing

Contributions are welcome! Please fork this repository and create a pull request.
