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
![WhatsApp Image 2025-09-19 at 11 02 17_609f0333](https://github.com/user-attachments/assets/be4c0e8c-302c-4e94-adca-14c27a386ad6)
![WhatsApp Image 2025-09-19 at 11 02 27_8f36e0a5](https://github.com/user-attachments/assets/f75f00a3-19c0-4cd4-accd-d954b0c976b4)
![WhatsApp Image 2025-09-19 at 11 02 36_ce5b7e85](https://github.com/user-attachments/assets/8d13b069-9e3b-4475-b3a0-847dc66505b4)



