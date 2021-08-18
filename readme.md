# CS3219 Task A1

## **Task A1: Introduction to Docker**
In this task, I have learnt to set up docker and implement a reverse proxy. This is done and shown in the Dockerfile.

The docker application will run a simple web server with the landing page in nginx-html/index.html.

#### How to deploy the docker:
1. Ensure that you have docker installed in your computer.
2. Either download the files via the Git GUI, or by the following command
  
        git clone https://github.com/kormingsoon/cs3219-taskA.git
3. Navigate the folder containing the Dockerfile and build the image. In this following code, the name of the image is named cs3219-webserver with a tag of 'v1'. Feel free to rename to anything else you like.

        docker build -t cs3219-webserver:v1
    
4. After building, run the image with the following command.

        docker run -d -p 80:80 cs3219-webserver:v1

5. Access the web application via http://localhost/ 

#### Additional Learning
1.  Nginx Reverse Proxy

While the reverse proxy in this instance is set to localhost for in the nginx's default.conf, I learnt that the reverse proxy's capabilities extends beyond such a simple usecase. More complicated usecase allows it to act as load distributor as well as help to mediate traffic. 



