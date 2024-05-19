## GRPC Integration
This guide shows step by step how to integrate GRPC Files for Swift language
### What needs to be installed ?
- MacOS
- Xcode
- Homebrew
- protobuf
- grpc
- grpc-swift

#### Installations
1.Homebrew
> /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
2. protobuf
> brew install protobuf
3. grpc
> brew install grpc
4. grpc-swift
> brew install grpc-swift
#### Adding GRPC dependencies with Swift Package Manager

## Exporting the proto file
> protoc --swift_out=. vpncenter.proto -> Proto Name
> protoc “Proto Name” --grpc-swift_opt=Client=true,Server=false --grpc-swift_out=. 
