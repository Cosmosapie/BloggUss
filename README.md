# BloggUss : A Blog Application

**Project Setup:**

We began by initializing a Node.js project and installing essential dependencies: Express.js for handling server-side logic, Mongoose for interacting with MongoDB, Body-parser for parsing incoming request bodies, and EJS for templating. After setting up the Express server, we connected it to a MongoDB database to store and retrieve blog data. We configured EJS to handle dynamic content rendering and set up static file serving to manage assets like CSS and images.

**Database Schema:**

We created a Mongoose schema for blog posts, defining the necessary fields such as title and content to structure our data efficiently. This schema served as a blueprint for our blog posts, allowing us to enforce consistency and perform operations on our MongoDB database. By implementing this schema, we facilitated seamless interaction between our application and the database, ensuring that data could be easily stored, retrieved, and manipulated.

**Routing and Views:**

We defined routes to handle various user interactions, such as displaying all blog posts, composing new ones, and viewing individual posts. These routes were designed to map user requests to appropriate server responses. For rendering dynamic content, we created EJS templates for different views: a home page to list all posts, a compose page for creating new posts, and individual post pages to display specific entries. This setup ensured a smooth and interactive user experience.

**Application Functionality:**

We implemented CRUD (Create, Read, Update, Delete) operations for blog posts, allowing users to add new posts, view existing ones, edit content, and delete entries. To enhance the application's functionality, we integrated user authentication, enabling secure login and registration processes. We also added a comment system to foster user interaction.

The program runs on localhost at port 1423, ensuring it works as expected in a local development environment.
