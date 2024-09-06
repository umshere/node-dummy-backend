# Blog Post API

This is a simple Express.js backend application that provides API endpoints for managing blog posts.

## Features

- Get all posts
- Get a specific post by ID
- Create a new post

## Prerequisites

- Node.js (v12 or higher recommended)
- npm (comes with Node.js)

## Installation

1. Clone the repository:
   ```
   git clone https://github.com/yourusername/blog-post-api.git
   cd blog-post-api
   ```

2. Install dependencies:
   ```
   npm install
   ```

## Usage

1. Start the server:
   ```
   node app.js
   ```

2. The server will start running on `http://localhost:8080`

## API Endpoints

- `GET /posts`: Retrieve all posts
- `GET /posts/:id`: Retrieve a specific post by ID
- `POST /posts`: Create a new post

## Example Requests

### Get all posts