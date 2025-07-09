# ErcNftMetadataIndexerAPINext

## Description

This repository houses a framework for generating generative NFT collections using deterministic cellular automata rulesets, allowing for provably unique and visually diverse assets with minimal on-chain storage by storing only the initial seed and transition rules.

## Features

- Indexes ERC-721 and ERC-1155 token metadata from multiple EVM-compatible chains.
- Stores indexed NFT metadata in a PostgreSQL database optimized for fast querying and filtering.
- Implements a GraphQL API for efficient and flexible retrieval of NFT metadata.
- Caches frequently accessed NFT metadata using Redis to reduce database load and improve response times.
- Supports real-time updates to the index via websocket subscriptions to blockchain event streams.
- Provides configurable retry mechanisms for handling transient network errors during blockchain data ingestion.
- Deploys a serverless architecture using AWS Lambda and API Gateway for scalability and cost-effectiveness.
- Validates NFT metadata against a configurable schema to ensure data integrity.
## Installation

```bash
pip install git+https://github.com/Lyne6666/ErcNftMetadataIndexerAPINext.git
```

## Usage

```bash
python -m ercnftmetadataindexerapinext --verbose
```

## Contributing

We welcome contributions! Here's how to get started:

1. Fork this repository
2. Create a new branch for your feature (`git checkout -b feature/your-feature`)
3. Commit your changes (`git commit -am 'Add some awesome feature'`)
4. Push to the branch (`git push origin feature/your-feature`)
5. Open a Pull Request

## License

Distributed under the MIT License. See `LICENSE` for more information.
