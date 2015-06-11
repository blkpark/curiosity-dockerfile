FROM debian:latest
MAINTAINER Graham Lee <ghmlee@cosmos.io>

RUN apt-get update && apt-get install -y libssl-dev && rm -rf /var/lib/apt/lists/*

ADD curiosity /usr/bin/
ENTRYPOINT ["curiosity"]