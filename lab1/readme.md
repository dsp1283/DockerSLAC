# Lab 1
## Clone the repository via HTTPS
- ``git clone https://github.com/dsp1283/DockerSLAC.git``
## Have a Python script and no local installation?
In the cloned repo, go to ``/lab1/sample-python``
### Build a Docker image with the name "sample-python"
``docker build -t sample-python .``
### Run the new image in interactive mode
``docker run sample-python -it /bin/sh``
### Execute the python script
``python ./Add.py``
