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


1. Basic HTML Page:
   

   - Create a plain HTML page named `index.html` with some content (e.g., "Hello, Docker!").

3. Nginx Configuration:

   - Create an Nginx configuration file named `nginx.conf` that serves the `index.html` page.

   - Configure Nginx to listen on port 80.
  
   - ![image](https://github.com/mohanvedase/Docker_custom_webserver/assets/139565500/6055e3a0-3d87-4b6f-848b-0b5905cbc818)

  
4. Dockerfile:

   - Create a `Dockerfile` to define the Docker image.

   - Use an official Nginx base image.
  
   - ![image](https://github.com/mohanvedase/Docker_custom_webserver/assets/139565500/f1ffb280-ddf6-4d68-9e8a-fd25a915a395)


   - Copy the `index.html` and `nginx.conf` files into the appropriate location in the container.

   - Ensure that the Nginx server is started when the container is run.

5. Building the Docker Image:

   - Build the Docker image using the `Dockerfile`.
  

6. Push the image on ECR

  - Make the public repository and push them on the ECR
  - ![image](https://github.com/mohanvedase/Docker_custom_webserver/assets/139565500/e841129f-fc07-4dc8-84c0-56ac0de7be1d)


6. Screenshots


   - ![image](https://github.com/mohanvedase/Docker_custom_webserver/assets/139565500/36e157ba-1310-4926-9be3-26e13903f857)
   - ![image](https://github.com/mohanvedase/Docker_custom_webserver/assets/139565500/01aa4cc7-dd82-442b-b9f8-f2e6d1f24339)
   - ![image](https://github.com/mohanvedase/Docker_custom_webserver/assets/139565500/1e4607b6-f1f8-413e-961d-357f8d4be5e2)
   - ![image](https://github.com/mohanvedase/Docker_custom_webserver/assets/139565500/ebf5c13c-a942-418c-921d-0f5a184b0cf0)
   - ![image](https://github.com/mohanvedase/Docker_custom_webserver/assets/139565500/4b317148-3aeb-4d4a-87d8-73e25638e762)

   -------------------------------------------------------------DONE-------------------------------------------------------



