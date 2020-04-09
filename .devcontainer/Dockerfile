FROM ubuntu:20.04
LABEL Name=elephant-devcontainer Version=0.0.0

# install required packages
RUN apt-get update
RUN apt-get -y --fix-missing install git
RUN apt-get -y --fix-missing install gcc
RUN apt-get -y --fix-missing install libz-dev
RUN apt-get -y --fix-missing install libevent-dev
RUN apt-get -y --fix-missing install libssl-dev
RUN apt-get -y --fix-missing install curl
RUN apt-get -y --fix-missing install xz-utils
RUN apt-get -y --fix-missing install rsync
RUN apt-get -y --fix-missing install gnupg
RUN DEBIAN_FRONTEND="noninteractive" TZ="Europe/Brussels" apt-get -y --fix-missing install tzdata
RUN curl -fsS https://dlang.org/install.sh | bash -s dmd
