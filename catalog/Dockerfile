FROM golang:1.16

WORKDIR /go/src/
COPY . .
RUN GOOS=linux go build -ldflags="-s -w"
CMD ["./catalog"]