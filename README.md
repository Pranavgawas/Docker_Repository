# Docker_Repository
docker repository for testing

## docker build command
docker build -t my-image:1.0 .

## docker run command
docker run -d -p 3000:3000 --name my-container my-image:1.0

## docker login
docker login -u pranavgawas

## dockerhub push
docker push {username}/{imagename}:{tagname}

## docker images witch is running
docker ps

## docker stop container
docker stop container-id

## docker remove container
docker rm container-id

## docker remove images 
docker rmi image-id



# if i created docker image on loccaly and want to deploy on docker i have to do below step
## first log in

# Build the image with the correct tag
```
docker build -t myportfolio:1.1.0 .
```

# Tag the local image with the desired repository and tag
```
docker tag myportfolio:1.1.0 docker.io/pranavgawas/myportfolio:1.1.0
```
# Push the tagged image to Docker Hub
```
docker push docker.io/pranavgawas/myportfolio:1.1.0
```
