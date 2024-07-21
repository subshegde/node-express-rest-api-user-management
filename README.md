# node-express-rest-api-user-management

This Node.js and Express.js application sets up a simple REST API for managing user data stored in MOCK_DATA.json. It includes endpoints for retrieving all users (/api/users), retrieving a specific user by ID (/api/users/:id), updating a user (PATCH /api/users/:id), deleting a user (DELETE /api/users/:id), and adding a new user (POST /api/users). The server runs on port 8000 and uses fs for file operations and express.urlencoded() middleware for handling form data.
