FROM python:3
ENV PYTHONUNBUFFERED=1
RUN apt-get update && apt-get -y install vim
WORKDIR /django
COPY requirements.txt requirements.txt
RUN pip3 install -r requirements.txt
