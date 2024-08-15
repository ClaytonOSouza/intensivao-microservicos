FROM golang:1.23

WORKDIR /go/src/
COPY . .
RUN GOOS=linux go build -ldflags="-s -w"
CMD ["./checkout"]