FROM golang:alpine

WORKDIR /go/src/web

COPY ./ ./

RUN go mod download

RUN go build -o /web-app

EXPOSE 32777

ENTRYPOINT /web-app 
