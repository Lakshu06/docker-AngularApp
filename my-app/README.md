# MyApp

This project was generated with [Angular CLI] version 8.3.2.

node version v10.16.3

nginx version version: nginx/1.14.0 



## to build docker images
docker build -t dockerimagesname:prod .

docker build -t dockerimagesname:prod --build-arg configuration="" .

docker build -t dockerimagesname:prod --build-arg configuration="staging" .


## to run docker image

docker run -p 80:80 my-angular-project:prod




