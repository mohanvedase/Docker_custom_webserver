# Docker_custom_webserver
The objective of this assignment is to familiarize yourself with Docker and containerization by Dockerizing a simple HTML page using Nginx as the web server.
## Prerequisites
Create ec2 instance and configure the security group to  the required ports.
![image](https://github.com/mohanvedase/Docker_custom_webserver/assets/139565500/ac52c7d0-47df-4a5b-b48a-26e0f5d84e2e)

Install Docker
![image](https://github.com/mohanvedase/Docker_custom_webserver/assets/139565500/119c49a7-0334-4cfd-9309-3fdd4fbb03fc)
```
sudo apt install docker.io -y
```
Install Nginx
![image](https://github.com/mohanvedase/Docker_custom_webserver/assets/139565500/c731785a-cc1d-411c-be8f-30f59b93c25e)
```
sudo apt install nginx -y
```

1. Basic HTML Page:

   - Create a plain HTML page named `index.html` with some content (e.g., "Hello, Docker!").
     

2. Nginx Configuration:

   - Create an Nginx configuration file named `nginx.conf` that serves the `index.html` page.

   - Configure Nginx to listen on port 80.

3. Dockerfile:

   - Create a `Dockerfile` to define the Docker image.

   - Use an official Nginx base image.

   - Copy the `index.html` and `nginx.conf` files into the appropriate location in the container.

   - Ensure that the Nginx server is started when the container is run.

4. Building the Docker Image:

   - Build the Docker image using the `Dockerfile`.

5. Push the image on ECR

  - Make the public repository and push them on the ECR
