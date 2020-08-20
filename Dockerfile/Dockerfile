FROM golang:latest
WORKDIR /1a2b
ADD . /1a2b
RUN cd /1a2b  && go get -u github.com/gin-gonic/gin && go get github.com/satori/go.uuid && go build
EXPOSE 8085
ENTRYPOINT ./1a2b
