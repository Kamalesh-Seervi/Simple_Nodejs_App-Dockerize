# Simple_Nodejs_App-Dockerize

**Steps to follow :**

1) docker build -t [name]:[tag] .
2) docker run -d -p [portNo]:80 [name]:[tag]   #it listens port 80 because in code app.listen(80) is coded.

**To stop the docker container:**

1) docker ps    #to check the name of the container.
2) docker stop [name of the container]

or

3) docker rm -f [name of the container] #for force delete if docker container crashes.

**To delete an image in docker:**

1) docker rmi [name of the image]
