# Nginx JWT Exctractor Example

This project shows the basics of extracting information from a JWT and logging.

# Running the App

Runs as a couple of custom docker containers.

From root, type `docker-compose up --build`.

To see sample responses make GET requests with a JWT as bearer token to:

- http://localhost:8080/ to see the token decoded and response back from a node.js app
- http://localhost:8080/nginx to see the respone returned from a custom nginx JS function.
- http://localhost:8080/jwt to see the contents of the "sub" field in the JWT.
