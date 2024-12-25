FROM ubuntu:latest

RUN apt update && apt --assume-yes install iproute2 &&  apt --assume-yes install iputils-ping && apt --assume-yes install netcat-openbsd && setcap cap_net_raw+p /usr/bin/ping
