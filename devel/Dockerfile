FROM golang:1.23rc2
MAINTAINER Mike Purvis

RUN go get github.com/smira/aptly

ADD aptly.conf /etc/aptly.conf
VOLUME ["/aptly"]
