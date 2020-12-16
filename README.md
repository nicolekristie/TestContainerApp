# TestContainerApp
Create a docker file to run simple Hello World App.

git clone: https://github.com/nicolekristie/TestContainerApp.git

BUILD THE image
 docker build . -t testapp 
Run the image:
 docker run --rm -it -p 3000:3000/tcp testapp:latest
 
View app running in container on localhost:3000 

Confirm that docker container is running 
  docker ps 
