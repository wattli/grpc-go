gRPC in 3 minutes (Go)
======================

In current dir:

$ go help gopath

$ # ensure the PATH contains $GOPATH/bin

$ export PATH=$PATH:$GOPATH/bin

One tab, do (the server is running already)

$ go run helloworld/greeter_server/main.go

The other tab, do

$ go run helloworld/greeter_client/main.go

At client side, it should receive response message.

At server side, it should print out client's identity information.
