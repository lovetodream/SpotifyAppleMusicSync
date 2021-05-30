# Development Environment

A mongodb instance you can run in development, if you don't have one running already.

```sh
docker-compose up
```

This will start a mongodb instance on port 27017 with username `root` and password `password`.

Don't forget to add an appropriate connection string to your environment.

```sh
export DATABASE_URL=mongodb://root:password@localhost:27017/{{database}}
```
