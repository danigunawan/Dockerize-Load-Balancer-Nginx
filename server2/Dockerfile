FROM ubuntu:18.04

RUN apt-get update \
    && apt-get -y install python
RUN mkdir serverroot
 
COPY index.html serverroot/

WORKDIR /serverroot
CMD python -m SimpleHTTPServer
