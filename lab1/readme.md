# Lab 1

## Clone the repository via SSH
- [Setup SSH Keys](https://confluence.atlassian.com/bitbucket/set-up-an-ssh-key-728138079.html)
- ``git clone git@github.com:dsp1283/DockerSLAC.git``

## Clone the repository via HTTPS
- ``git clone https://github.com/dsp1283/DockerSLAC.git``
- You will always need to provide your username and password when pushing to the repository

## Have a Python script and no local installation?
In the cloned repo, go to ``/lab1/sample-python``
### Build a Docker image with the name "sample-python"
``docker build -t sample-python .``
### Run the new image in interactive mode
``docker run sample-python -it /bin/sh``
### Execute the python script
``python ./Add.py``
