<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
</head>
<body>

  <h1>📝 Blog-Verse - Full Stack Blog Platform</h1>

  <p><strong>Blog-Verse</strong> is a dynamic full-stack blogging platform that allows users to register, login, create, and explore technical blogs across various categories. The app is built using the <strong>MERN stack</strong> and supports secure authentication with Passport.js.</p>

  <h2>🔧 Features</h2>
  <ul>
    <li>User registration and secure login with Passport.js</li>
    <li>Create, read, update, and delete blog posts</li>
    <li>Category-based filtering of blogs</li>
    <li>Responsive, user-friendly interface</li>
    <li>Backend API with Express and MongoDB</li>
  </ul>

  <h2>🗂️ Folder/File Structure</h2>
  <div class="folder-structure">
    ├── <code>client/</code> – Frontend React code<br>
    │&nbsp;&nbsp;&nbsp;&nbsp;├── <code>components/</code> – Reusable UI components<br>
    │&nbsp;&nbsp;&nbsp;&nbsp;├── <code>pages/</code> – Main pages (Home, Blog, Profile, etc.)<br>
    │&nbsp;&nbsp;&nbsp;&nbsp;├── <code>App.js</code>, <code>index.js</code> – React root<br>
    ├── <code>server/</code> – Backend (Node.js + Express)<br>
    │&nbsp;&nbsp;&nbsp;&nbsp;├── <code>routes/</code> – Blog and auth API routes<br>
    │&nbsp;&nbsp;&nbsp;&nbsp;├── <code>models/</code> – Mongoose schemas<br>
    │&nbsp;&nbsp;&nbsp;&nbsp;├── <code>config/</code> – Passport config<br>
    │&nbsp;&nbsp;&nbsp;&nbsp;├── <code>server.js</code> – Entry point<br>
    ├── <code>package.json</code> (x2) – For client and server<br>
    ├── <code>.env</code> – Environment variables<br>
  </div>

  <h2>🚀 How to Run Locally</h2>
  <ol>
    <li>Clone the repository: <code>git clone https://github.com/yourusername/blog-verse</code></li>
    <li>Navigate to client and server folders and run <code>npm install</code></li>
    <li>Set up your <code>.env</code> with MongoDB URI and session secret</li>
    <li>Run backend: <code>npm start</code> inside <code>server/</code></li>
    <li>Run frontend: <code>npm start</code> inside <code>client/</code></li>
    <li>Visit <code>http://localhost:3000</code> to explore</li>
  </ol>

  <h2>🌐 Live Demo</h2>
  <p><a href="https://bloggverse.netlify.app/" target="_blank">Try Blog-Verse Live</a></p>

  <h2>📸 Preview</h2>
  <img src="client/assets/blog-preview.png" alt="Blog-Verse App Screenshot" style="width:100%;max-width:600px;border:1px solid #ccc;">

  <h2>📦 Tech Stack</h2>
  <ul>
    <li>MongoDB</li>
    <li>Express.js</li>
    <li>React.js</li>
    <li>Node.js</li>
    <li>Passport.js for Authentication</li>
  </ul>

  <h2>🙋‍♂️ Author</h2>
  <p>Created by Gautam Srivastava | <a href="https://github.com/Gremreaper">GitHub: Gremreaper</a></p>

</body>
</html>
