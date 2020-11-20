# uarm-grpc-gateway
gRPC gateway for uArm Controller

# Development Environment Preparation

## Go

Download and install the latest version (Go 1.15 at the time of writing) from [here](https://golang.org/doc/install).

## gRPC and protoc

Install the utility tools.
```
go get google.golang.org/grpc
go get github.com/golang/protobuf/protoc-gen-go
go get github.com/stormcat24/protodep
go get github.com/fullstorydev/grpcurl/...
go install github.com/fullstorydev/grpcurl/cmd/grpcurl
```

Retrieve the Protocol Buffers dependencies.
```
protodep up
```
