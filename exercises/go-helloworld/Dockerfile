FROM golang:alpine3.8

LABEL maintainer ="Michael Murithi"

WORKDIR /go/src/app

ADD . .

COPY . /go/scr/app

RUN  go build -o helloworld

EXPOSE 6111

CMD [ "./helloworld"]
