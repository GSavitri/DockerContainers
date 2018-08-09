Description: 	The Docker-compose file runs two services:1.	nginx : Acts as proxy to the web server2.	Apache httpd web server
Pre requisite:-	Install and run the Docker daemon.-	Host machine has Internet connectivity to connect to Docker-hub and pull the images.Steps for execution:-	Go to working directory where Docker-compose.yml file is present.-	Run the command: 		Docker-compose up -	Docker-compose.yml pulls the images from Dockerhub and runs the containers.

-	Check localhost:7890 to see the working container.


Cleanup:
 Run Docker-compose down to clean up the environment.

 