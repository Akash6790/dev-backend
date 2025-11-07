📌 Project Overview

This project is a simple file-based task manager backend built using Node.js, Express.js, and EJS templates. Instead of using a database, the application stores each task as a separate .txt file in the /files directory. Users can create tasks by submitting a title and description, and each task is saved as a physical file on the server.

The project helps beginners understand core backend concepts such as file handling, routing, templating, and form processing without adding database complexity.

✅ Features
1. Create Tasks

Users can submit a form with a title and description.

The backend automatically generates a .txt file with the task content.

The file name is generated using the title.

2. Read Tasks

All existing task files in the /files folder are read dynamically.

Each file name is displayed on the home page with a "Read More" link.

Clicking it opens a detailed view of that task.

3. File Handling using Node.js

Uses fs.writeFile() to create new tasks.

Uses fs.readdir() to fetch all files.

Uses fs.readFile() to display the content.

4. Server-Side Rendering with EJS

The UI is rendered using EJS templates (index.ejs and show.ejs).

Tailwind CSS is used for fast and responsive UI styling.

✅ Technologies Used
Backend

Node.js

Express.js

File System Module (fs)

Path Module

Frontend

EJS (Embedded JavaScript Templates)

Tailwind CSS

✅ Purpose of the Backend Project

This project is designed to help you understand:

🔹 Core backend fundamentals

Routing

Middleware

Request handling

Form submission (POST method)

🔹 File handling

Creating, reading, and managing files on the server

Using Node's fs module

🔹 Server-Side Rendering

Passing data from Express routes to EJS templates

Dynamic rendering of file names and file content

🔹 Folder and project structure

Organizing routes

Using public/ for static assets

Using views/ for templates
