  
FROM python:3.8

RUN mkdir /app
WORKDIR /app

RUN apt-get update && apt-get install -y mongodb-org


COPY requirements.txt ./
RUN pip install --no-cache-dir -r requirements.txt

COPY . .
