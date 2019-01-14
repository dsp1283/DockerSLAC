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
### Run the image again
``docker run sample-layers``
### Edit Dockerfile
Make ``COPY test.sh .`` the last instruction
### Edit test.sh
### Run the image again
``docker run sample-layers``
