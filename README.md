# Permanent todolist

A simple web application that allows users to create, edit, and delete tasks in a blog-style list. The app is built with Node.js, Express, EJS, and PostgreSQL for data management. Styling is done with plain CSS.

## Features
- Add new posts to the list.
- Edit existing posts directly on the interface.
- Delete posts from the list.
- Responsive design with a clean and minimal user interface.

## Technologies Used
**Backend**: Node.js, Express
**Frontend**: HTML, CSS, EJS (No frontend frameworks used)
**Database**: PostgreSQL
**Templating Engine**: EJS

## Setup Instructions
### 1. Clone the repository
You can clone this repository to your local machine by running the following command:
git clone https://github.com/JamalChemlalDEV/permanent-todolist.git

### 2. Install dependencies
npm install

### 3. Set up PostgreSQL Database
- Ensure PostgreSQL is installed and running.
- Create a new database named permalist_db.
- Run the SQL script to create the required table:
  CREATE TABLE items (
  id SERIAL PRIMARY KEY,
  title VARCHAR(100) NOT NULL
  );
