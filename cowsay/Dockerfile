FROM debian:wheezy

MAINTAINER Ryo Kawana <ryo.kawana.1@gmail.com>
RUN apt-get update && apt-get install -y cowsay fortune
COPY entrypoint.sh /

ENTRYPOINT ["/entrypoint.sh"]
