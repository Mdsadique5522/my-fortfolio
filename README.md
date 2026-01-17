# Professional Portfolio Website

A dynamic and professional portfolio website built with HTML, CSS, JavaScript, and Node.js backend with MongoDB Atlas.

## Features

- **Dynamic Projects**: Add and delete projects permanently stored in database
- **Contact Form**: Receive contact messages stored in database
- **Professional Design**: Attractive and modern UI
- **Responsive**: Works on all devices

## Setup

1. Clone or download the project
2. Install dependencies: 
pm install
3. Create a .env file with your MongoDB Atlas connection string:
   `
   MONGODB_URI=mongodb+srv://username:password@cluster.mongodb.net/portfolio?retryWrites=true&w=majority
   `
4. Run the server: 
pm start
5. Open http://localhost:5000 in your browser

## Usage

- View projects on the homepage
- Click "Add New Project" to add projects (stored permanently)
- Use the contact form to send messages (stored in database)
- Delete projects using the delete button

## Technologies

- Frontend: HTML, CSS, JavaScript
- Backend: Node.js, Express
- Database: MongoDB Atlas
- Icons: Font Awesome
