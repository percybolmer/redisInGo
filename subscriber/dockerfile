FROM golang:1.15

RUN mkdir /app
WORKDIR /app
COPY . .
RUN go mod init subscriber
RUN go build -o subscriber

CMD ["/app/subscriber"]