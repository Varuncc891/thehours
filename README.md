# The Hours
The Hours is a news aggregator application that allows users to register, log in, and access curated news content. It employs JWT-based authentication with password hashing via bcrypt, ensuring safe credential storage and validation.



**Technologies Used**

**Frontend**
React.js, React Router, Axios. 


**Backend (user login and registration)**
Node.js, Express.js, jsonwebtoken (JWT), bcrypt.js 


**Database (storing passwords)**
MongoDB.


**Features**

- User registration with email and password.

- Secure login and authentication using JSON Web Tokens (JWT)

- Passwords are hashed and salted using bcrypt before storage

- Persistent user sessions via token-based authorization.


**Installation and Setup**

1. Clone the repository
   <pre>git clone https://github.com/Varuncc891/thehours.git</pre>

2. Navigate to the project directory
   <pre>cd thehours</pre>

3. Install server dependencies
   <pre></pre>

4. Install client dependencies
   <pre>cd ../frontend
   npm install
   </pre>

5. Start the development server
   Frontend
   <pre>npm start</pre>
   Backend
   <pre>node server</pre>



