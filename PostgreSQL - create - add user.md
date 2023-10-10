# PostgreSQL creating and add user

The following steps is how you can create a PostgresSQL database, create a user, and add user to database.

1 - Login to PostgresSQL interactive session `sudo -u postgres psql`
2 - Create database by typing `CREATE DATABASE mydatabase;` replace `mydatabase` with the name you want to use. Note: Always end your commands with `;`.
3 -  Create the user and password for your database `CREATE USER myuser WITH PASSWORD 'password';` replace `myuser` with the name wish to use for the user and `password` with a secure password
4 - Grant user access to the database `GRANT ALL PRIVILEGES ON DATABASE mydatabase TO myuser;`