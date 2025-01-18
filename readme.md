For generate *.pb.go files use that command:

protoc -I proto proto/sso/sso.proto --go_out=./gen/go --go_opt=paths=source_relative --go-grpc_out=./gen/go/  --go-grpc_opt=paths=source_relative
