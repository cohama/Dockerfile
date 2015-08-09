FROM ubuntu:12.04
MAINTAINER cohama <cohama@live.jp>

RUN apt-get update
RUN apt-get install -y vim git
RUN git clone git://github.com/thinca/vim-themis

ENTRYPOINT ["/vim-themis/bin/themis"]
