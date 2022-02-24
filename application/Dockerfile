FROM golang
WORKDIR /go/src/github.com/andykuszyk/prometheus-histogram-example/application
COPY ./* ./
COPY ./vendor ./vendor
CMD go run main.go
