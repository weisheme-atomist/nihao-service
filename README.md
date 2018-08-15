# nihao-service
my new project

Based on seed project `johnsonr:flux-flix-service`

## Running the Project

First install Mongo db if you don't have it already. Easiest way is:
```
docker run --name mongodb --rm -p 27017:27017 bitnami/mongodb:latest
```

Then, start the server with:

```
mvn spring-boot:run
```

Test by visiting `http://localhost:8090/movies`
