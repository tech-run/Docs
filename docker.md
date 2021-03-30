# Docker

## Handy Docker commands 
```
docker images          # List of local images. 
docker rmi {image_id}		# remove image

docker ps -a			# show running containers 
docker stop ${container_id}	# stop container
docker rm ${container_id}	# remove stopped container

docker run ${image_id}:${tag_id} 

docker exec -it ${container_id} /bin/bash	# runs unix commands within container. 

```
## Docker links 
 - [Docker](https://www.docker.com/)
 - [Docker Hub](https://hub.docker.com/)
