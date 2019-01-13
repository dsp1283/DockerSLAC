FROM python:3-alpine

WORKDIR /usr/src/app

COPY requirements.txt ./
##ADD Add.py /
RUN pip install --no-cache-dir -r requirements.txt
COPY . .
