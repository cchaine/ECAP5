# ECAP5
Educational Computer Architecture Platform

## Running the docker build environment
Running the following commands will create the docker image and start the container :
```bash
docker build -t ecap5 .
docker run --platform linux/amd64 -v `pwd`:/home/ubuntu/ecap5 --name ecap5 -it ecap5
```
