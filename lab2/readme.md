# Docker for Noobs - Lab 2
## Clone the repository via HTTPS
- ``git clone https://github.com/dsp1283/DockerSLAC.git``
## Go the the lab source
In the cloned repo, go to ``/lab2/sample-layers``
### Build a Docker image with the name "sample-layers"
``docker build -t sample-layers .``
### Run the new image
``docker run sample-layers``
### Edit test.sh
### Rebuild the image
``docker build -t sample-layers .``
### Run the image again
``docker run sample-layers``
### Edit Dockerfile
Move ``COPY test.sh .`` to be the second to last instruction
### Rebuild the image
``docker build -t sample-layers .``
### Edit test.sh
### Rebuild the image
``docker build -t sample-layers .``
### Run the image again
``docker run sample-layers``
