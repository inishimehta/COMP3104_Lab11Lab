
# Run following command on terminal

docker build --tag=hellodocker .

docker image ls

docker run -p 4000:80 hellodocker
docker run --detach --publish 4000:80 hellodocker

docker container stop CONTAINER_ID
docker rm CONTAINER_ID

docker container ls