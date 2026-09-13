# btcd-walletrpc

> btcd · wallet · rpc

[![Go 1.22+](https://img.shields.io/badge/go-1.22+-00ADD8)](https://go.dev)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![Build](https://img.shields.io/badge/build-passing-brightgreen)]()

btcd wallet RPC shell — derive, stub balances, stdlib CLI.

## Features

- BTC derivation path m/84'/0'/0'
- Local vault JSON with XOR wrap
- SHA-256 stand-in keys — no live RPC
- stdlib CLI via flag

## Prerequisites

- Go 1.22+
- Git

## Getting Started

```bash
git clone <repo-url>
cd btcd-walletrpc
make build
./bin/btcdrpc -help
```

## CLI Usage

```bash
make test
go run ./cmd/btcdrpc -help
```

## Project Structure

```
cmd/btcdrpc/main.go
internal/config/config.go
internal/crypto/keys.go
internal/wallet/wallet.go
internal/wallet/wallet_test.go
```

## Background

Go Bitcoin ops search walletrpc, not bitcoin-wallet.

## License

This project is licensed under the MIT License — see the [LICENSE](LICENSE) file for details.


---

## Topics

![btcd](https://img.shields.io/badge/btcd-111827?style=flat-square) ![walletrpc](https://img.shields.io/badge/walletrpc-111827?style=flat-square) ![btcd-walletrpc](https://img.shields.io/badge/btcd%20walletrpc-111827?style=flat-square) ![cryptocurrency](https://img.shields.io/badge/cryptocurrency-111827?style=flat-square) ![wallet](https://img.shields.io/badge/wallet-111827?style=flat-square) ![blockchain](https://img.shields.io/badge/blockchain-111827?style=flat-square) ![web3](https://img.shields.io/badge/web3-111827?style=flat-square) ![bitcoin](https://img.shields.io/badge/bitcoin-111827?style=flat-square)

`btcd` `walletrpc` `btcd-walletrpc` `cryptocurrency` `wallet` `blockchain` `web3` `bitcoin` `ethereum` `hd-wallet` `open-source` `golang` `go`

Search: btcd-walletrpc · btcd · wallet · rpc · btcd wallet RPC shell — derive, stub balances, stdlib CLI.

---

<sub>btcd wallet RPC shell — derive, stub balances, stdlib CLI.</sub>
