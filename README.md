# nuget-proxy-docker

Very simple example of using Nginx to proxy Nuget requests.

### Building the docker image
- Make sure docker is installed
- Navigate to repsoitry
- in terminal `docker buil -t <image name> .`

### Run new image
- docker `run --name <custom name> -d -p 8080:80 <image name>`
  
  Port 8080 being the host port
