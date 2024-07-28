==>iDiscuss - Coding Forum

iDiscuss is a web-based forum platform where users can discuss various coding and development topics. The platform allows users to create threads, post comments, and browse different categories related to programming languages, frameworks, and technologies.

==>Features
        User Authentication: Register and log in to participate in discussions.
        Create Threads: Users can create new discussion threads.
        Post Comments: Users can comment on existing threads.
        Search Functionality: Search for threads and comments.
        Category Browsing: Browse discussion categories.
        Responsive Design: Mobile-friendly and responsive layout using Bootstrap.

==>Technologies Used
        Frontend: HTML, CSS, Bootstrap
        Backend: PHP
        Database: MySQL
        Server: Apache

==>Set up the database:
        Create a MySQL database named idiscuss.
        Import the idiscuss.sql file into your database.
        Configure the database connection:
        Edit the partials/dbconnect.php file to match your database credentials.
        php
        Copy code
        $servername = "localhost";
        $username = "yourusername";
        $password = "yourpassword";
        $database = "idiscuss";

        $conn = mysqli_connect($servername, $username, $password, $database);
        Start the server:
        If you're using XAMPP or WAMP, move the project folder to the htdocs directory.
        Start Apache and MySQL from the control panel.

==>Usage
        Register a new user account or log in with an existing account.
        Browse categories to find topics of interest.
        Create new threads to start discussions or comment on existing threads.
        Use the search functionality to find specific threads or comments.

==>File Structure

        idiscuss/
        ├── partials/
        │   ├── _header.php
        │   ├── _footer.php
        │   ├── dbconnect.php
        │   ├── _handlelogin.php
        │   ├── _handlelogout.php
        │   ├── _handleSignup.php
        │   └── _handlecontact.php
        ├── css/
        │   └── style.css
        ├── js/
        │   └── script.js
        ├── img/
        │   └── ... (images used in the project)
        ├── index.php
        ├── about.php
        ├── contact.php
        ├── threadlist.php
        ├── thread.php
        └── search.php