FROM golang:latest AS builder

WORKDIR /app/helloworld

COPY helloworld.go .

RUN go build helloworld.go

CMD ["./helloworld"]