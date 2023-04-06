# go-client-ip
Simple utility to capture client's IP address while calling an end point.

`go mod init mevinod.com/ip`
`go mod tidy`
`go build -o ip`


`curl -v -X  GET http://localhost:8080/getIp`

Docker image: `karikevinod/ip-capture:v1.0.0`

Hosted and available at: `https://mevinod.com/ping`
