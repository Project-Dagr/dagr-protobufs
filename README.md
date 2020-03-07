dagr-protobufs


Install nanopb
install protoc
install protoc-dart

## Instructions
```
protoc --nanopb_out=-v:../src -I=../proto mesh.proto

protoc --dart_out=../lib/ .\dagr.proto
```