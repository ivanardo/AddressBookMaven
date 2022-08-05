# AddressBookMaven
Protocol buffers practice with [Google's Java tutorial](https://developers.google.com/protocol-buffers/docs/javatutorial)

Protobuf compiler releases [here](https://github.com/protocolbuffers/protobuf/releases).

After loading the protobuf compiler you can add it to the system variables.

Command for generate proto classes:  protoc -I="src/main" --java_out="src/main/java"  "src/main/resources/addressbook.proto" 