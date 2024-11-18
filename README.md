# Login-page
This repo contains the yaml code for the deployment of a web server for login page using cloud formation template having the server on public subnet, mysql database for storing the login details in the private subnet with S3 if needed and IGW for public subnet and NAT gateway for the private subnet.

# For table creation
Create table for the database created. Ensure table is created or else create manually using this query.

CREATE TABLE users (
    id INT AUTO_INCREMENT PRIMARY KEY,
    username VARCHAR(25) NOT NULL,
    password VARCHAR(25) NOT NULL
);
