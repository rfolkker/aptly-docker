FROM golang:1.22.5
MAINTAINER Mike Purvis

RUN go get github.com/smira/aptly

ADD aptly.conf /etc/aptly.conf
VOLUME ["/aptly"]
