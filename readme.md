For generate code from proto files:
1) use command: "task generate" or
2) protoc -I proto proto/sso/*.proto --go_out=./gen/go --go_opt=paths=source_relative --go-grpc_out=./gen/go/  --go-grpc_opt=paths=source_relative
