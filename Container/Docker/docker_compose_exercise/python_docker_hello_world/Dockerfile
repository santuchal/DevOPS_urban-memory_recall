FROM ubuntu:20.04
MAINTAINER Santu Chall
RUN apt-get update
RUN apt-get install -y python3

WORKDIR usr/app/src

COPY hello.py ./

CMD ["python3", "./hello.py"]
