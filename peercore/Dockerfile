FROM ubuntu:xenial
MAINTAINER Linfeng Liang <lianglinfeng@gmail.com>

ENV HOME /build

RUN apt-get update && apt-get install -y --no-install-recommends \
    automake \
    build-essential \
    cmake \
    git \
    libffi-dev \
    libglib2.0-dev \
    libpcre3-dev \
    libmount-dev \
    wget \
    && apt-get clean && rm -rf /var/lib/apt/lists/* /tmp/* /var/tmp/*

WORKDIR /build
