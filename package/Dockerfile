FROM ruby:4.0.1-trixie

RUN apt-get update && \
    apt-get install -y git make rpm golang && \
    gem install fpm

WORKDIR /work

ENTRYPOINT [ "/bin/bash" ]
