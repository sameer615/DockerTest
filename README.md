# DockerTest
# Build the docker image 
$ docker image build -t username/http:v1 .
# To run the docker image 
docker container run --name containername -d username/httpd:v1
