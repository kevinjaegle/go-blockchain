# Go Blockchain – Part 1 (Basic Prototype)

This repository contains a minimal blockchain prototype written in Go.

## What is implemented (Part 1)
- Block structure: Timestamp, Data, PrevBlockHash, Hash
- SHA-256 hashing by concatenating block fields
- Blockchain as an ordered list of blocks
- Genesis block
- Adding new blocks linked to the previous block hash
- Printing the chain

## Run
```bash
go run ./cmd/blockchain

## Example Output
Prev. hash:
Data: Genesis Block
Hash: ...

Prev. hash: ...
Data: Send 1 BTC to Ivan
Hash: ...