# Version 0.0.1
FROM ubuntu:latest
MAINTAINER neoma <matengneo@gmail.com>

# install vim, python & pip
RUN apt-get update && apt-get install vim python python-pip python-dev

# install tensorflow (no GPU, only CPU)
RUN pip install --upgrade pip &&  pip install --upgrade https://storage.googleapis.com/tensorflow/linux/cpu/tensorflow-0.8.0-cp27-none-linux_x86_64.whl