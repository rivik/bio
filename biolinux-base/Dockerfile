FROM ubuntu:14.04
ADD sources.list /etc/apt/
RUN apt-get -y update
RUN DEBIAN_FRONTEND=noninteractive apt-get install -y -q python-software-properties software-properties-common
RUN DEBIAN_FRONTEND=noninteractive add-apt-repository ppa:nebc/bio-linux
