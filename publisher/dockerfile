FROM golang:1.15

RUN mkdir /app
WORKDIR /app
COPY . .
RUN go mod init publisher
RUN go build -o publisher

CMD ["/app/publisher"]