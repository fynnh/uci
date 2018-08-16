FROM i386/ubuntu:14.04

RUN echo "deb http://dl.bintray.com/fynnh/debian trusty main" | tee -a /etc/apt/sources.list && \
  apt-get update && \
  apt-get install -y --allow-unauthenticated \
  build-essential \
  cmake \
  lua5.2 \
  libjson-c-dev \
  liblua5.2-dev \
  ubox
