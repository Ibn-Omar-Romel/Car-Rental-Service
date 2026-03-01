<div align="center">
  <img src="https://img.shields.io/badge/Language-PHP-777BB4.svg" alt="PHP">
  <img src="https://img.shields.io/badge/Database-MySQL-4479A1.svg" alt="MySQL">
  <img src="https://img.shields.io/badge/Frontend-Bootstrap_5.3-7952B3.svg" alt="Bootstrap">
  
  <h1>🚗 Car Rental Management System</h1>
  <h3>A comprehensive web-based vehicle reservation platform</h3>
</div>

<hr />

<h2>📝 Project Overview</h2>
<p align="justify">
  This Car Rental Service is a full-stack web application built to streamline the vehicle booking process. It features a robust multi-role architecture, providing dedicated interfaces and functionalities for <b>Admins</b>, <b>Drivers</b>, and <b>Users</b>.
</p>

<h2>🌟 Key Features</h2>
<ul>
  <li><b>Multi-Role Authentication:</b> Secure login and registration for Admins, Drivers, and Customers.</li>
  <li><b>Admin Dashboard:</b> Full control over car inventory, driver assignments, and user management.</li>
  <li><b>Booking System:</b> Users can browse available cars, view full details, and manage their booking history.</li>
  <li><b>Responsive UI:</b> Styled with custom CSS and <b>Bootstrap 5.3.2</b> for a seamless mobile and desktop experience.</li>
  <li><b>Database Integration:</b> Managed via MySQL with pre-configured relational queries.</li>
</ul>

<hr />

<h2>📂 Project Structure</h2>
<pre>
📁 CAR_RENTAL_SERVICE
├── 📂 All PHP Files           # Core backend logic and frontend views
│   ├── Admin_*.php            # Administrator dashboard and controls
│   ├── User_*.php             # Customer interfaces and bookings
│   ├── Driver_*.php           # Driver management and profiles
│   ├── Connection.php         # MySQL Database connection handling
│   └── main.css               # Custom styling
├── 📂 bootstrap-5.3.2-dist    # Local Bootstrap framework files
├── 📂 Dataset
│   └── database_Query.sql     # SQL schema and dummy data
└── 📂 All Buttons / Images    # Static graphical assets
</pre>

<hr />

<h2>🛠️ Tech Stack</h2>
<table width="100%">
  <tr>
    <th>Category</th>
    <th>Technologies Used</th>
  </tr>
  <tr>
    <td><b>Backend</b></td>
    <td>PHP (Vanilla)</td>
  </tr>
  <tr>
    <td><b>Frontend</b></td>
    <td>HTML5, CSS3, Bootstrap 5.3.2, JavaScript</td>
  </tr>
  <tr>
    <td><b>Database</b></td>
    <td>MySQL</td>
  </tr>
</table>

<hr />

<h2>⚙️ Setup Instructions</h2>

<h3>1. Clone the Repository</h3>
<pre>
git clone https://github.com/Ibn-Omar-Romel/Car-Rental-Service.git
</pre>

<h3>2. Server Environment</h3>
<p>Ensure you have a local server environment running, such as <b>XAMPP</b>, <b>MAMP</b>, or <b>WAMP</b>.</p>
<ul>
  <li>Move the project folder into your server's root directory (e.g., <code>htdocs</code> for XAMPP).</li>
</ul>

<h3>3. Database Configuration</h3>
<ul>
  <li>Open phpMyAdmin.</li>
  <li>Create a new database for the project.</li>
  <li>Import the <code>database_Query.sql</code> file located in the <code>Dataset/</code> folder.</li>
  <li>Update the database credentials in <code>All PHP Files/Connection.php</code> if necessary.</li>
</ul>


<div align="center">
  <p>© 2026 | Developed by Romel</p>
</div>
