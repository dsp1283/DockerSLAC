### Build the image named node-server
`docker build -t node-server .`
### Run the container
- `-d` = detached mode
- `-p` = attach public port to private port
`docker run -p 49160:8080 -d node-server`
### View any running containers
`docker ps`
### Hit the url using the public port
- `curl -i localhost:49160`
- Open a browser and go to http://localhost:49160
### Shut down the container
- `docker ps` and copy the CONTAINER ID
- `docker container stop <CONTAINER ID>`
