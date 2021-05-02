# GRPC com GO!

## Introdução

- [x] Descobrir o que é o GRPC
- [x] Métodos GRPC (unary, server stream, client stream, bidirecional)
- [x] Instalar o PROTOC e GRPC

```bash
apt install -y protobuf-compiler
go get google.golang.org/protobuf/cmd/protoc-gen-go \
         google.golang.org/grpc/cmd/protoc-gen-go-grpc
export PATH="$PATH:$(go env GOPATH)/bin"
```

- [x] Instalar extensão do protoc

## Primeiro passo

- [x] Criar arquivo proto
- [x] Gerar o arquivo de proto

## Segundo passo

- [x] Implementar métodos GRPC no server
- [x] Implementar método GRPC no client

## Conclusão

- [x] Realizar a comunicação
