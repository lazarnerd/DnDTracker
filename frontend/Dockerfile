FROM ubuntu:22.04

ENV PATH="${PATH}:${HOME}/.local/bin"

RUN apt update && apt install -y npm curl
RUN npm i -g n
RUN n stable