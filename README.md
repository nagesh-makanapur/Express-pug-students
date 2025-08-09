🎓 Student Management System (Express + Pug + MongoDB)
A simple yet functional Student Management System built with Node.js, Express, Pug, and MongoDB.
This application allows you to add, view, update, and delete student records in a clean and responsive interface.

📸 App Preview – Student Management System




📌 Features
➕ Add Students – Input student details via a form

📋 View Students – Display all stored students in a table view

✏️ Edit Students – Update existing student information

❌ Delete Students – Remove student records from the database

🎨 Pug Templating – Clean and dynamic server-side rendered UI

🗄 MongoDB Integration – Persistent data storage

📦 Tech Stack
Backend: Node.js, Express.js

Templating Engine: Pug

Database: MongoDB with Mongoose

Styling: CSS (Static files in public/)

```
📂 Project Structure
csharp
Copy
Edit
Express-pug-students/
  ├── models/            # Mongoose schemas
  ├── public/             # Static assets (CSS, JS)
  ├── views/              # Pug templates
  ├── server.js           # Main server file
  ├── package.json        # Dependencies & scripts
  └── README.md           # Documentation
⚙️ Installation & Setup
1️⃣ Clone the repository

bash
Copy
Edit
git clone https://github.com/nagesh-makanapur/Express-pug-students.git
cd Express-pug-students
2️⃣ Install dependencies

npm install
3️⃣ Start MongoDB locally

mongod
4️⃣ Run the application
npm start
📍 The app will be running at: http://localhost:3000

🗃 Database Info
Database Name: myStudent
Collections: students
