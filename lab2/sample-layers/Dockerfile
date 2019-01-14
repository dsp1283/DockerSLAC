FROM python:3-alpine

WORKDIR /app

COPY test.sh .

COPY requirements.txt requirements.txt
RUN pip install --no-cache-dir -r requirements.txt

CMD sh ./test.sh
