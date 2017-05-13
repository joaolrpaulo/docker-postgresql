# How to run

Build the image

```bash
docker build --rm=true -t YOURUSERNAME/postgresql:9.6 .
```

Modify docker-compose.yml (add your username) and then run your image to persist data.

```bash
docker-compose up
```

To access data from docker image you should have PostgresSQL installed on your local machine.

What are the benefits of this image?

A clean development environment on your machine :)
