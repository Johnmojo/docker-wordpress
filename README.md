**_ docker-wordpress _**

This is a template that can be used to quickly spin up a WordPress site using Docker.

1. Run `docker-compose up -d` to start the containers.
2. Open `http://localhost:{YOUR_PORT_NUMBER}` in your browser.
3. Profit.

Your .env should have the following:

```
CONTAINER_NAME='wordpress'
DB_ROOT_PASSWORD='admin'
DB_NAME='wordpress'
DB_USER='admin'
DB_PASSWORD='admin'
WORDPRESS_PORT=3000
WORDPRESS_USER='admin'
WORDPRESS_PASSWORD='admin'
```

Change the values as you see fit.
