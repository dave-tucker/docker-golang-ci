FROM golang:1.4

RUN apt-get update && apt-get install -y wget socat
RUN go get code.google.com/p/go.tools/cmd/cover
RUN go get github.com/mattn/goveralls
