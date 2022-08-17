FROM ubuntu:18.04

COPY . .

ENV PATH "$PATH:/usr/local/go/bin:/home/user/go/bin:/home/user/.cargo/bin"

#install dependencies
RUN apt update
RUN apt install wget nano ncdu locate -y

RUN bash setup.sh
USER 1AR