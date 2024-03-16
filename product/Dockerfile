FROM golang:1.21.7

WORKDIR /go/src/
COPY . .
RUN GOOS=linux go build -ldflags="-s -w"
CMD ["./product"]