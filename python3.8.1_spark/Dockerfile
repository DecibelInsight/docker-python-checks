FROM python:3.8.1-buster

MAINTAINER Gonzalo Bandeira <gbandeira@decibelinsight.com>

# Add java
RUN apt-get update
RUN apt-get install default-jdk -y

# Install app dependencies
WORKDIR /app
# Added full path, as that is what docker builder needs
COPY python3.8.1_spark/requirements.txt requirements.txt
RUN pip install -r requirements.txt

