WordPress + MySQL + phpMyAdmin Setup with Docker Compose
========================================================

Overview
--------

This setup lets you quickly deploy WordPress, MySQL, and phpMyAdmin using Docker Compose. WordPress will be available on port 8080 and phpMyAdmin will be accessible on port 8081. The MySQL database for WordPress is pre-configured with the following details:

- Database Name: wordpress
- Database User: wordpressuser
- Database Password: wordpresspassword

Instructions
------------

Run the following command to start the setup:

   docker compose up

This command will start the services, and your WordPress site will be ready in no time.

Access Details
--------------

WordPress:
- URL: `http://localhost:8080`

phpMyAdmin:
- URL: `http://localhost:8081`
- Login using the following credentials:
  - Username: wordpressuser
  - Password: wordpresspassword

Notes
-----

- Ensure Docker is installed on your system before running the setup.
- For any modifications, edit the `docker-compose.yml` file as per your requirements.
