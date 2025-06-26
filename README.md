# My Blog Application

This is a simple single-page blog application built with HTML, CSS, and JavaScript. It uses a mock REST API created with `json-server` to persist and manage blog post data.


## Technologies Used

* **HTML5**: For the structure of the application.
* **CSS3**: For styling and layout.
* **JavaScript (ES6+)**: For fetching data, handling user interactions, and rendering content dynamically.
* **`json-server`**: A Node.js package used to create a fake REST API that saves data to a `db.json` file.

## Setup Instructions

Follow these steps to set up and run the project on your local machine.

### Prerequisites

You must have **Node.js** and **npm** (Node Package Manager) installed on your computer. You can download them from the official Node.js website.

To check if they are installed, open your terminal and run:
`node -v`
`npm -v`

### 1. Installation

First, you need to install `json-server` globally on your system. This allows you to run the mock API from any directory.

```bash
npm install -g json-server
2. Running the API Backend
Navigate to your project folder in the terminal (the folder containing index.html, style.css, script.js, and db.json). Then, run the following command to start the json-server backend.
json-server --watch db.json --port 3000

3. Running the Frontend
To view the frontend of your application, you open the index.html file in your web browser. 
4. Usage
 * View Posts: Open the index.html file in your browser. The posts from your db.json file will be displayed in the left sidebar.
 * Create a Post: Fill out the "Create New Post" form on the right and click "Add New Post".
 * View Details: Click on a post title in the sidebar to view its full details.
 * Edit a Post: Click the "Edit Post" button to show the edit form, make changes, and click "Update Post".
 * Delete a Post: Click the "Delete Post" button to remove it.
