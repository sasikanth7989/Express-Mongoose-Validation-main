Implement Status Codes and Error Handling in Express + Mongoose
📌 Project Overview

This project demonstrates how to implement HTTP status codes and error handling for invalid requests in a CRUD REST API built with Express and Mongoose.

🚀 Getting Started
1. Setup Project

Reuse the Node.js project from the CRUD API or create a new one:

mkdir express-mongoose-error
cd express-mongoose-error
npm init -y
npm install express mongoose body-parser

2. Create Schema & Model

Connect to MongoDB (schoolDB) using Mongoose.

Define a Student schema with fields:

name (String, required)

rollNo (Number, required, unique)

branch (String)

year (Number)

email (String)

3. Add CRUD Routes with Status Codes

Implement routes with proper responses:

200 OK → Successful GET request

201 Created → Resource created successfully

400 Bad Request → Validation or bad data

404 Not Found → Resource not found

500 Internal Server Error → Server/DB issue

4. Global Error Handling

Add an Express middleware to catch unexpected errors and return a JSON response with a 500 status.

5. Run the Project

Start the server:

node app.js


Open http://localhost:3000 in Postman or browser to test.

📂 Project Structure
express-mongoose-error/
 ├── app.js
 ├── package.json
 └── README.md

✅ Output
![Picture1](https://github.com/user-attachments/assets/bacb237a-e37a-4ab5-a7e2-983067d99a09)

![Picture2](https://github.com/user-attachments/assets/5b33f2ba-07ea-4798-a4e0-a2928ec79333)
![Picture3](https://github.com/user-attachments/assets/80875faf-84ad-4973-8924-1146c058820b)

