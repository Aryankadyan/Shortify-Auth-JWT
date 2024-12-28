# Shortify #
<h2>Custom URL Shortener with Node.js and JWT Authentication</h2>
<h3>Overview</h3>
This project is a custom URL shortener built with Node.js. It features user authentication and secure API access using JSON Web Tokens (JWT). The app allows users to shorten URLs, manage their shortened links, and ensures secure access to the API endpoints.
<h3>Features</h3>
<ul>
<li>User authentication (registration and login)</li>
<li>Secure API access with JWT authentication</li>
<li>Shorten URLs with unique identifiers</li>
<li>Retrieve original URLs from shortened links</li>
<li>User-specific URL management</li>
<li>Error handling and validation</li>
</ul>
<h3>Prerequisites</h3>
Before running this project, ensure you have the following installed:
<li>Node.js (v14 or later)</li>
<li>npm</li>
<li>MongoDB (or a MongoDB Atlas account for cloud hosting)</li>
<h3>Installation</h3>
<li>1. Clone the repository:</li>
<blockquote>
  git clone https://github.com/Aryankadyan/Shortify
  <br>
cd your-repo-name
</blockquote>
<li>2.Install dependencies</li>
<blockquote>
  npm install
</blockquote>
<li>3.Set up environment variables:</li>
<blockquote>
  PORT=3000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret_key
</blockquote>
<li>4.Start the development server:</li>
<blockquote>
  npm start
  <br>
  The server will run at http://localhost:3000 by default.
</blockquote>
<h3>Routes</h3>
POST/URL - Generates a new short URL and returns the shortened URL in the format example.com/random-id.
<br>
GET/:id - Redirects the user to the original URL.
<br>
GET/URL/analytics/:id - Returns the clicks for the provided short id.
<h3>Technologies Used</h3>
<li>Node.js</li>
<li>Express.js</li>
<li>MongoDB(Mongoose)</li>
<li>JSON Web Tokens(JWT)</li>



