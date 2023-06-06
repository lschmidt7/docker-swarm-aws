FROM golang:1.20
COPY . .
RUN go build -o server server.go
CMD [ "./server" ]