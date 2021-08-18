# CS3219 Task A

## Task A1: Introduction to Docker
In this task, I have learnt to set up docker and implement a reverse proxy. This is done and shown in the Dockerfile.

#### How to deploy the docker:
1. Ensure that you have docker installed in your computer
2. Either download the files via the Git GUI, or by the following command

    Insert git clone command
3. Once downloaded, run 
* -d signifies background mode running
* -v map current directory to the destination 

    Insert docker build
    docker run -d -p 8000:80 --name cs3219-docker nginx

4. Access localhost 

5. docker pull nginx
6. 