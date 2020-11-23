FROM python:3.8.1-slim
MAINTAINER Gonzalo Bandeira <gbandeira@decibelinsight.com>

# Install app dependencies
WORKDIR /app
# Added full path, as that is what docker builder needs
COPY python3.8.1/requirements.txt requirements.txt
RUN pip install -r requirements.txt

