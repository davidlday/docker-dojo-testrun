FROM ubuntu:latest

ENV PATH=/usr/games:$PATH

RUN apt-get update \
  && apt-get install -y cowsay

CMD ["cowsay", "\"Let's keep MOOOOOving\""]
