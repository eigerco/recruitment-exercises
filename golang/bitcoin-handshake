# Bitcoin node handshake

_Spec v1 (March 28, 2024)_

Pick a publicly available bitcoin node implementation - which itself doesn't need to be written in Go - and write a
[network handshake](<https://en.wikipedia.org/wiki/Handshake_(computing)>) for it in Go, including instructions on how to test it.

## Requirements

- Both the target node and the handshake code should compile at least on Linux.
- The solution has to perform a full **protocol-level** (post-TCP) handshake with the target node.
- The solution can not use the node implementation as a dependency.
- The submitted code can not use existing P2P libraries for the handshake.

### Non-requirements

- The solution can ignore any post-handshake traffic from the target node, and it doesn't have to keep the connection alive.

## Evaluation

- **Quality**: the solution should be idiomatic and adhere to Go coding conventions.
- **Performance**: the solution should be as fast as the handshake protocol allows, and it shouldn't block resources.
- **Security**: the network is an inherently untrusted environment, and it should be taken into account.
- **Minimalism**: any number of dependencies can be used, but they should be tailored to the task.
