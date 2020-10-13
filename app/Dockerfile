FROM python:3.8-alpine

WORKDIR /usr/src/flask_app
COPY requirements.txt .
RUN pip3 install --no-cache-dir -r requirements.txt
COPY . .
