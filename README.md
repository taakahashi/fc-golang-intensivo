# Instruções
https://go.dev/dl/

https://github.com/niXman/mingw-builds-binaries/releases

Instructions: Download version x86 > Extract to "C:\mingw64\bin" > Add "C:\mingw64\bin" in "PATH" to System Variables)

# Comandos Úteis
    - go env GOOS=windows go build main.go
    - go env -w CGO_ENABLED=1
    - go mod tidy
    - go run main.go


# Comandos Docker
    - docker-compose up -d
    - docker-compose ps
    - docker-compose exec goapp bash

    - apt install sqlite3
    - sqlite3 orders.db
    - Paste here the "create table"
    - go mod tidy
    - go run cmd/consumer/main.go

    - docker rm -f $(docker ps -a -q)
    - docker volume rm $(docker volume ls -q)