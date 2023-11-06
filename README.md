# The Problem

You can't have messages named Desrciptor, Parser etc due to the [issue](https://github.com/protocolbuffers/protobuf/issues/12291) in protoc. It does escapes field names, but doesn't do the same for types.