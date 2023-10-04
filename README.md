使用docker:
1. 建構docker 
    docker build -t lottery-server .
2. 啟動docker並把port: 1234開放
    docker run -d -p 1234:1234 --name lottery-server lottery-server

不使用docker:
1. 直接 go run server.go 即可啟動server端服務