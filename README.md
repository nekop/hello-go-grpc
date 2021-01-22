# hello-grpc-go

```
$ grpcurl -plaintext -d '{"name":"foo"}' localhost:50051 helloworld.Greeter.SayHello
{
  "message": "Hello foo"
}
```