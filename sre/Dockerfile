FROM golang:latest

WORKDIR /app

COPY httpServer_crash.go ./
COPY index.html ./
COPY error.html ./
# COPY restart.sh ./
RUN go build -o main .

EXPOSE 8080

CMD ["./main"]
