FROM ubuntu:22.04

ENV PATH="${PATH}:${HOME}/.local/bin"

RUN apt update && apt install -y curl python3 python3-pip
RUN curl -sSL https://install.python-poetry.org | python3 -