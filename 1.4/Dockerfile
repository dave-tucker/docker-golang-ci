FROM golang:1.4

RUN apt-get update && apt-get install -y iptables
RUN go get golang.org/x/tools/cmd/cover
RUN go get github.com/modocache/gover
RUN go get github.com/mattn/goveralls
