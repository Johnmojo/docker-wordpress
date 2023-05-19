**_ docker-wordpress _**

This is a template that can be used to quickly spin up a WordPress site using Docker.

1. Clone the repo.

2. Create an .env file in the root directory with the following values:

```
CONTAINER_NAME=wordpress
HOST_PORT=3000
DB_PORT=3306

ROOT_PASSWORD=anyRootPassword
DATABASE_NAME=wordpress-db
USER=wpuser
PASSWORD=databasePassword
```

3. Run `docker-compose up -d` to start the containers.

4. Open `http://localhost:3000` in your browser.
