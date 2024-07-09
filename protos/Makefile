all: generate

generate:
	protoc -I proto proto/gRPC_service/gRPC_service.proto --go_out=./gen/go/ --go_opt=paths=source_relative --go-grpc_out=./gen/go --go-grpc_opt=paths=source_relative