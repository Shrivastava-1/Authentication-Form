<h2 align="center">🔐 These project is based on user authentication form</h2>

<p>This project is a <strong>secure authentication system</strong> that allows users to <strong>register, log in, and log out</strong> using a <strong>PHP-based backend</strong> and <strong>MySQL database</strong>. It includes error handling, session management, and a responsive UI.</p>

<h2>✨ Features</h2>
<ul>
  <li>✅ <strong>User Registration</strong> – Users can sign up with a name, email, age, and password.</li>
  <li>✅ <strong>Login System</strong> – Validates user credentials before granting access.</li>
  <li>✅ <strong>Secure Password Handling</strong> – Uses hashing for password security.</li>
  <li>✅ <strong>Session Management</strong> – Keeps users logged in until they log out.</li>
  <li>✅ <strong>Forgot Password</strong> – Allows users to reset passwords.</li>
  <li>✅ <strong>Edit Profile</strong> – Users can update their details.</li>
  <li>✅ <strong>Logout</strong> – Ends the user session securely.</li>
</ul>

<h2>🛠️ Technologies Used</h2>
<ul>
  <li><strong>Frontend:</strong> HTML, CSS (<code>styles.css</code> for styling)</li>
  <li><strong>Backend:</strong> PHP (handles authentication logic)</li>
  <li><strong>Database:</strong> MySQL (stores user information)</li>
  <li><strong>Python Script:</strong> (<code>Database_Table.py</code>) for creating the database and tables</li>
</ul>

<h2>📂 Project Structure</h2>
<pre>
/authentication-system  
│── config.php        # Database connection  
│── index.php         # Login page  
│── register.php      # Registration page  
│── home.php          # User dashboard  
│── forgot.php        # Forgot password feature  
│── edit.php          # Edit user profile  
│── logout.php        # Logout functionality  
│── styles.css        # UI styling  
│── Database_Table.py # Script to create database/tables  
</pre>

<h2>🚀 Setup Guide</h2>

<h3>1️⃣ Clone the Repository.</h3>
<pre>
git clone https://github.com/your-username/authentication-system.git
cd authentication-system
</pre>

<h3>2️⃣ Set Up the Database</h3>
<ul>
  <li>Open <code>Database_Table.py</code> and <strong>run the script</strong> to create the MySQL database and tables.</li>
  <li>Ensure MySQL is running and update <code>config.php</code> with your <strong>database credentials</strong> if needed.</li>
</ul>

<h3>3️⃣ Run the Application</h3>
<ul>
  <li>Use <strong>XAMPP or any local server</strong> to run the project.</li>
  <li>Open your browser and visit:</li>
</ul>
<pre>http://localhost/authentication-system/index.php</pre>
<ul>
  <li>Register a new user and log in to test the system.</li>
</ul>

<h2>📌 Notes</h2>
<ul>
  <li>Modify <code>config.php</code> with your <strong>database credentials</strong> if required.</li>
  <li>Ensure the <code>Database_Table.py</code> script runs successfully before using the application.</li>
</ul>
