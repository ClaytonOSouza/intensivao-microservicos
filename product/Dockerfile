FROM golang:1.24rc1

WORKDIR /go/src/
COPY . .
RUN GOOS=linux go build -ldflags="-s -w"
CMD ["./product"]