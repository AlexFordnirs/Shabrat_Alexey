FROM ubuntu

WORKDIR /

RUN apt update
RUN apt upgrade
RUN apt install -y neofetch
RUN neofetch >> neo.log
RUN uname -a > satrt.log
RUN df -h >> satrt.log
