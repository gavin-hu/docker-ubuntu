FROM ubuntu:15.10

MAINTAINER Gavin Hu <haozhonghu@hotmail.com>

RUN apt-get -y install wget
RUN mv /etc/apt/sources.list /etc/apt/sources.list.bak \
    && wget http://mirrors.163.com/.help/sources.list.wily -O /etc/apt/sources.list \
    && apt-get update

ENTRYPOINT ["/bin/bash"]
