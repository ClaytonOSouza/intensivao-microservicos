FROM golang:1.24.2

WORKDIR /go/src/
COPY . .
RUN GOOS=linux go build -ldflags="-s -w"
CMD ["./payment"]