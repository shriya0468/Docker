Flask Docker App
This is a simple Flask web application that runs inside a Docker container. It responds with "Hello World" when accessed.

Setup & Run
1) Build the Docker image:
docker build -t flask-docker-app .
2)Run the container:
docker run -p 5000:5000 flask-docker-app
3)Open a browser and visit:
http://localhost:5000



