FROM golang:1.24-alpine

EXPOSE 8081

WORKDIR /go/src/app

COPY . .

RUN go build -o auth-api

CMD /go/src/app/auth-api
