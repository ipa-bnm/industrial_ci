FROM ubuntu:16.04

MAINTAINER "ROS Industrial" "https://github.com/ros-industrial"

# Install packages
RUN apt-get update -qq \
    && apt-get -qq install -y \
        git \
        sudo \
        lsb-release \
        python-pip \
        wget \
        2>&1 >/dev/null \
    && apt-get clean 2>&1 >/dev/null
ENV IN_DOCKER 1
ENV TERM xterm
