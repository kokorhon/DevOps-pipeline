FROM golang:1.16
EXPOSE 8080

ENV REQUEST_ORIGIN=http://127.0.0.1:5000/

WORKDIR /usr/src/app

COPY . .

RUN go build

RUN test ./..

CMD ["./server"]