# stock-price-proto

Protocol Buffers definitions for stock-price-repository gRPC services.

## Usage

This repository is cloned into the main application repository during build:

```bash
git clone https://github.com/Code0716/stock-price-proto.git proto-definitions
buf generate proto-definitions
```

## Development

After modifying proto files:

```bash
buf lint
buf format -w
git commit -am "Update proto definitions"
git push
```
