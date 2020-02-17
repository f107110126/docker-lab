FROM ubuntu:bionic
RUN apt update && apt upgrade -y
RUN DEBIAN_FRONTEND=noninteractive apt install -y apache2 apache2-utils php
EXPOSE 80
CMD apache2ctl -D FOREGROUND