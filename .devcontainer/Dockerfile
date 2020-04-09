FROM ubuntu:20.04
LABEL Name=elephant-devcontainer Version=0.0.0

# install required packages
RUN wget https://netcologne.dl.sourceforge.net/project/d-apt/files/d-apt.list -O /etc/apt/sources.list.d/d-apt.list
RUN apt-get update --allow-insecure-repositories
RUN apt-get -y --allow-unauthenticated install --reinstall d-apt-keyring
RUN apt-get update
RUN apt-get -y --fix-missing install git
RUN apt-get -y --fix-missing install gcc
RUN apt-get -y --fix-missing install libz-dev
RUN apt-get -y --fix-missing install libevent-dev
RUN apt-get -y --fix-missing install libssl-dev
RUN apt-get -y --fix-missing install curl
RUN apt-get -y --fix-missing install xz-utils
RUN apt-get -y --fix-missing install rsync
RUN apt-get install dmd-compiler dub
