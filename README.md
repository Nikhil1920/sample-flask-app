# About

This is a simple flask app that can show server resource usage and calculate fibonacci numbers.

You can use the fibonacci numbers calculator by sending a GET request to the following url:

/fibonacci

followed by a query parameter with the number you want to calculate.

You can use the fibonacci calculator to generate load on the server by giving it a large number as a query parameter.

# Docker

To build the image:
`docker build -t <give-tag-name> .`

To run the docker container:
`docker run -d -p 8080:8080 <image-name>`
