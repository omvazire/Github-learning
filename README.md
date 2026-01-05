<h1>🏡 UrbenNest — Full Stack Rental Marketplace</h1>

<p>
UrbenNest is a comprehensive <b>full-stack web application inspired by Airbnb</b>.
Built using the <b>MERN backend ecosystem</b> and <b>EJS</b> for dynamic server-side rendering,
it serves as a robust platform for users to list, discover, and review unique stays around the world.
</p>

<hr/>

<h2>🚀 Key Features</h2>
<ul>
  <li><b>Full CRUD Functionality:</b> Create, Read, Update, and Delete property listings.</li>
  <li><b>User Authentication:</b> Secure Signup, Login, and Logout using Passport.js.</li>
  <li><b>Image Management:</b> Seamless image uploads and cloud storage via Cloudinary.</li>
  <li><b>Interactive Reviews:</b> Dedicated rating and comment system for each listing.</li>
  <li><b>Authorization:</b> Only listing owners can edit or delete their properties.</li>
  <li><b>Data Validation:</b> Robust server-side schema validation using Joi.</li>
  <li><b>Responsive Design:</b> Optimized for mobile, tablet, and desktop using Bootstrap.</li>
</ul>

<hr/>

<h2>🛠️ Tech Stack</h2>

<h3>Backend</h3>
<ul>
  <li><b>Node.js</b> – JavaScript runtime environment</li>
  <li><b>Express.js</b> – Web framework for routing and middleware</li>
  <li><b>MongoDB</b> – NoSQL database for flexible data storage</li>
  <li><b>Mongoose</b> – Object Data Modeling (ODM) for MongoDB</li>
</ul>

<h3>Frontend</h3>
<ul>
  <li><b>EJS (Embedded JavaScript)</b> – Server-side templating engine</li>
  <li><b>Bootstrap 5</b> – Responsive and modern UI framework</li>
  <li><b>Vanilla CSS</b> – Custom styling for branding</li>
</ul>

<hr/>

<h2>📦 Detailed Package Breakdown</h2>

<table border="1" cellpadding="8" cellspacing="0">
  <thead>
    <tr>
      <th>Package</th>
      <th>Purpose</th>
      <th>Why it’s Essential</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>express</td>
      <td>Backend Framework</td>
      <td>Handles routing, requests, and responses</td>
    </tr>
    <tr>
      <td>mongoose</td>
      <td>Database Modeling</td>
      <td>Defines schemas for Listings, Reviews, and Users</td>
    </tr>
    <tr>
      <td>passport</td>
      <td>Authentication</td>
      <td>Industry-standard authentication middleware</td>
    </tr>
    <tr>
      <td>cloudinary</td>
      <td>Cloud Storage</td>
      <td>Secure hosting for uploaded images</td>
    </tr>
    <tr>
      <td>joi</td>
      <td>Schema Validation</td>
      <td>Ensures clean and valid data before DB insertion</td>
    </tr>
    <tr>
      <td>multer</td>
      <td>File Handling</td>
      <td>Processes image uploads from forms</td>
    </tr>
    <tr>
      <td>connect-mongo</td>
      <td>Session Storage</td>
      <td>Stores login sessions in MongoDB</td>
    </tr>
    <tr>
      <td>method-override</td>
      <td>RESTful Routes</td>
      <td>Allows PUT & DELETE requests via forms</td>
    </tr>
    <tr>
      <td>ejs-mate</td>
      <td>Layout Engine</td>
      <td>Enables reusable layouts and partials</td>
    </tr>
    <tr>
      <td>dotenv</td>
      <td>Security</td>
      <td>Protects sensitive credentials using environment variables</td>
    </tr>
  </tbody>
</table>

<hr/>

<h2>📂 Project Architecture (MVC)</h2>
<p>
The project follows the <b>Model–View–Controller (MVC)</b> design pattern for scalability and maintainability.
</p>

<pre>
UrbenNest/
├── controllers/    # Route logic (The Brain)
├── models/         # Mongoose schemas (The Data)
├── routes/         # Express route definitions
├── views/          # EJS templates (The UI)
│   ├── layouts/    # Shared layout (Navbar, Footer)
│   ├── listings/   # Listing-related views
│   └── users/      # Authentication views
├── public/         # Static assets (CSS, JS, Images)
├── utils/          # Error handling utilities
├── schema.js       # Joi validation schemas
└── app.js          # Application entry point
</pre>

<hr/>

<h2>🎯 What This Project Achieves</h2>
<ul>
  <li><b>Real-World Simulation:</b> Mirrors platforms like Airbnb and Zillow.</li>
  <li><b>Scalability:</b> Demonstrates large-scale backend structuring.</li>
  <li><b>Security First:</b> Password hashing, sessions, and authorization.</li>
  <li><b>Cloud Integration:</b> Professional image handling using Cloudinary.</li>
</ul>

<hr/>

<h2>📚 Learnings from this Project</h2>
<ul>
  <li>Mastering the MVC architecture</li>
  <li>Implementing secure authentication flows</li>
  <li>Building centralized error handling</li>
  <li>Managing database relationships (Users ↔ Listings ↔ Reviews)</li>
  <li>Handling environment variables securely</li>
</ul>

<hr/>

<h2>⚙️ Local Installation</h2>

<h3>Clone the Repository</h3>
<pre><code>git clone https://github.com/your-username/urben-nest.git
cd urben-nest</code></pre>

<h3>Install Dependencies</h3>
<pre><code>npm install</code></pre>

<h3>Environment Variables</h3>
<p>Create a <code>.env</code> file and add:</p>
<pre><code>CLOUDINARY_CLOUD_NAME=your_name
CLOUDINARY_KEY=your_key
CLOUDINARY_SECRET=your_secret
DB_URL=your_mongodb_atlas_url
SECRET=your_session_secret</code></pre>

<h3>Run the Application</h3>
<pre><code>node app.js</code></pre>

<p>Open <b>http://localhost:3000</b> in your browser.</p>

<hr/>

<h2>👨‍💻 Author</h2>
<p>
<b>Om Vazire</b><br/>
Full-Stack Web Developer (MERN)<br/>
🎓 B.E. Student – Mumbai University
</p>
