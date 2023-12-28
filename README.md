# Docker_Repository
docker repository for testing

## docker build command
docker build -t my-image:1.0 .

## docker run command
docker run -d -p 3000:3000 --name my-container my-image:1.0

## docker login
docker login -u pranavgawas

## dockerhub puch
docker push <username>/<imagename>:<tagname>

## docker stop container
docker stop container-id

## docker remove container
docker rm container-id

## docker remove images 
docker rmi image-id

