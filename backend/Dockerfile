FROM python:3.6.14-bullseye

ENV PYTHONUNBUFFERED 1

#change work directory
WORKDIR /app/backend

COPY ./requirements.txt ./

RUN pip install -r requirements.txt

COPY . . 
