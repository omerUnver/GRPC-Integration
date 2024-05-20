## GRPC Integration
This guide shows step by step how to integrate GRPC Files for Swift language
### What needs to be installed ?
- MacOS
- Xcode
- Homebrew
- protobuf
- grpc
- grpc-swift
- Evans
#### Installations
1.Homebrew
> /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
2. protobuf
> brew install protobuf
3. grpc
> brew install grpc
4. grpc-swift
> brew install grpc-swift
5. Evans
> brew tap ktr0731/evans && brew install evans

#### Adding GRPC dependencies with Swift Package Manager

## Exporting the proto file
1.Proto Swift File
> protoc --swift_out=. "protoName" -> Proto Name
2. grpc proto swift file
> protoc “Proto Name” --grpc-swift_opt=Client=true,Server=false --grpc-swift_out=. 
