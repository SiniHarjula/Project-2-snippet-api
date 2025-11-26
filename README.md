# Project 2 – Snippet API

This project is a backend API built with Node.js, Express, MongoDB Atlas, and Mongoose. Users can save, search, and retrieve code snippets.

Live deployment on Render:

https://project-2-snippet-api.onrender.com/

## How to run this project
### 1. Clone the repository
```bash
git clone https://github.com/SiniHarjula/Project-2-snippet-api.git

cd Project-2-snippet-api
```

### 2. Install dependencies
```bash
npm install
```

### 3. Create .env file and insert the following
```bash
MONGO_URI=your_mongo_atlas_string_here

PORT=3000
```

### 4. Start the server
```bash
node server.js
```
Now the API runs at
http://localhost:3000

## Postman examples of the API functionality

### Get all snippets 
<img width="990" height="796" alt="Näyttökuva 2025-11-24 234125" src="https://github.com/user-attachments/assets/f36ff986-d54c-491f-90a6-35103406c205" />

### Create a new snippet
<img width="985" height="649" alt="Näyttökuva 2025-11-24 234226" src="https://github.com/user-attachments/assets/b865dac8-b34e-40e2-8dd9-6c2e6cc41787" />

### Get snippet by id
<img width="911" height="554" alt="Näyttökuva 2025-11-24 234507" src="https://github.com/user-attachments/assets/12cd92f6-5877-48fa-aab0-b17c533f73ab" />

### Get snippets with filters
<img width="923" height="661" alt="Näyttökuva 2025-11-24 234646" src="https://github.com/user-attachments/assets/363cdb0b-44ee-422f-a6e0-e425a7a2e694" />

## Reflection and self-assessment

In this project, I learned how to connect a backend application to a MongoDB database and how to handle data inside it. 
This project helped me to understand how Mongoose works and how to define a schema that controls the structure of the data. 
Creating the schema helped me understand what fields each snippet should have, how validation works, and how the schema becomes a model that the API can actually use.

I also strengthened my skills in creating routes with Express. 
Building the GET and POST routes improved my knowledge of how the server receives requests, how data moves through req.body, and how the API returns JSON responses.  
Testing everything with Postman was really helpful because I could see exactly what the server returned and how the data looked in MongoDB Atlas after each request.

Another new thing I learned was why CORS is needed. Now I know that CORS allows a frontend to communicate with the backend even if they run on different ports. 
Without it, the browser would block the requests for security reasons.

Overall, this project made me feel more confident in backend technologies, and I think I met all the requirements of this project. 
I tested my API carefully and documented everything clearly. I feel that my understanding of backend development improved with this project. 
I really liked building this project, and I feel much more confident building routes, connecting to a database, and debugging issues.
