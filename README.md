# go-app
Built Restful Api using Gin Framework

## Build Docker image
Run docker build -t altsch/go-docker.

### Run a container
Run docker run -it -p 8000:8080 --mount type=bind,source="$(pwd)"/,target=/go/src/go-docker --name altsch-go-docker  altsch/go-docker

