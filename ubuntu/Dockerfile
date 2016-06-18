FROM ubuntu:wily

MAINTAINER Camille Meulien <cmeulien@heliostech.fr>

RUN apt-get update \
    && apt-get install -y ruby

RUN gem install kaigara

WORKDIR /root
