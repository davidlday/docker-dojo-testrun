FROM ubuntu:latest

ENV PATH=/usr/games:$PATH

RUN apt-get update \
  && apt-get install -y cowsay

ENTRYPOINT [ "cowsay" ]
CMD [ "This can be overriden" ]
