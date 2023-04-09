## Go Microservices
> Microservices sample written in Golang.

#### Connect mongo via MongoDB Compass
> mongodb://admin:yourpassword@localhost:27017/logs?authSource=admin&readPreference=primary&directConnection=true&ssl=false

#### Generate gRPC code from command line
> protoc --go_out=. --go_opt=paths=source_relative --go-
grpc_out=. --go-grpc_opt=paths=source_relative logs.proto 
