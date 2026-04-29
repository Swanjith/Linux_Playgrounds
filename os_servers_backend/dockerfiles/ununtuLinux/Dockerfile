FROM ubuntu:latest

RUN apt update && apt install -y \
    bash \
    readline-common \
    ncurses-term \
    curl wget vim nano git build-essential \
    && apt clean \
    && rm -rf /var/lib/apt/lists/*

ENV TERM xterm
CMD [ "bash" ]
