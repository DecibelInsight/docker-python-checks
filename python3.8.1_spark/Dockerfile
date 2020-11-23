FROM python:3.8.1-buster

MAINTAINER Gonzalo Bandeira <gbandeira@decibelinsight.com>

# Add java
RUN apt-get update
RUN apt-get install default-jdk -y

# Install app dependencies
COPY requirements.txt ./
RUN pip install -r requirements.txt

