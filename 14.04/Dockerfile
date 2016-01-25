FROM ubuntu:14.04

MAINTAINER Gavin Hu <haozhonghu@hotmail.com>

RUN apt-get -y install wget
RUN mv /etc/apt/sources.list /etc/apt/sources.list.bak \
    && wget http://mirrors.163.com/.help/sources.list.trusty -O /etc/apt/sources.list \
    && apt-get update
RUN apt-get -y install openjdk-7-jre

ENTRYPOINT ["/bin/bash"]
