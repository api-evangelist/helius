# Helius (helius)

Helius is a Solana developer platform offering Solana JSON-RPC, the Digital Asset Standard (DAS) API for NFTs/tokens, Enhanced Transactions, Webhooks, LaserStream gRPC streaming, Sender (transaction routing), Photon RPC, and Dedicated Nodes.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/helius/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/helius/refs/heads/main/apis.yml)

## Tags

- Web3
- Blockchain
- Solana
- RPC
- DAS
- Streams

## Timestamps

- **Created:** 2026-05-08
- **Modified:** 2026-05-29

## APIs

### Helius Solana RPC

Solana JSON-RPC and WebSocket endpoints with enhanced WebSockets, archival data, and staked connections.

- **Human URL:** [https://www.helius.dev/docs/rpc](https://www.helius.dev/docs/rpc)
- **Base URL:** `https://mainnet.helius-rpc.com/?api-key={apiKey}`

#### Tags

- JSON-RPC
- Solana
- WebSocket

#### Properties

- [Documentation](https://www.helius.dev/docs/rpc)
- [AsyncAPI](asyncapi/helius-asyncapi.yml) — [AsyncAPI Specification](https://www.asyncapi.com/docs/reference/specification/latest)
- [Postman Collection](collections/helius.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/helius.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Helius Digital Asset Standard (DAS) API

Solana JSON-RPC API for unified asset queries (compressed NFTs, regular NFTs, tokens) including getAsset, getAssetsByOwner, searchAssets.

- **Human URL:** [https://www.helius.dev/docs/das-api](https://www.helius.dev/docs/das-api)
- **Base URL:** `https://mainnet.helius-rpc.com/?api-key={apiKey}`

#### Tags

- JSON-RPC
- DAS
- NFT

#### Properties

- [Documentation](https://www.helius.dev/docs/das-api)
- [Postman Collection](collections/helius.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/helius.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Helius Enhanced Transactions API

REST API for parsed and human-readable Solana transaction history with token metadata.

- **Human URL:** [https://www.helius.dev/docs/api-reference/enhanced-transactions-api](https://www.helius.dev/docs/api-reference/enhanced-transactions-api)
- **Base URL:** `https://api.helius.xyz/v0`

#### Tags

- REST
- Transactions

#### Properties

- [Documentation](https://www.helius.dev/docs/api-reference/enhanced-transactions-api)
- [Postman Collection](collections/helius.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/helius.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Helius Webhooks

REST API for managing webhook subscriptions for Solana on-chain events with parsed transaction payloads.

- **Human URL:** [https://www.helius.dev/docs/webhooks](https://www.helius.dev/docs/webhooks)
- **Base URL:** `https://api.helius.xyz/v0/webhooks`

#### Tags

- REST
- Webhooks

#### Properties

- [Documentation](https://www.helius.dev/docs/webhooks)
- [Postman Collection](collections/helius.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/helius.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Helius LaserStream

Low-latency gRPC streaming of Solana account, slot, transaction, and block updates (Geyser-compatible).

- **Human URL:** [https://www.helius.dev/docs/laserstream](https://www.helius.dev/docs/laserstream)
- **Base URL:** `grpc://laserstream-mainnet.helius-rpc.com`

#### Tags

- gRPC
- Streaming

#### Properties

- [Documentation](https://www.helius.dev/docs/laserstream)
- [Postman Collection](collections/helius.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/helius.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Helius Sender

Parallel transaction routing through Helius and Jito for inclusion latency optimization.

- **Human URL:** [https://www.helius.dev/docs/sender](https://www.helius.dev/docs/sender)
- **Base URL:** `https://sender.helius-rpc.com`

#### Tags

- JSON-RPC
- Transactions
- Jito

#### Properties

- [Documentation](https://www.helius.dev/docs/sender)
- [Postman Collection](collections/helius.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/helius.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Helius Photon RPC (ZK Compression)

Indexed RPC for Solana ZK compression (compressed accounts).

- **Human URL:** [https://www.helius.dev/docs/photon](https://www.helius.dev/docs/photon)
- **Base URL:** `https://mainnet.helius-rpc.com`

#### Tags

- JSON-RPC
- ZK Compression

#### Properties

- [Documentation](https://www.helius.dev/docs/photon)
- [Postman Collection](collections/helius.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/helius.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Organization](https://github.com/helius-labs)
- [LinkedIn](https://www.linkedin.com/company/heliusapi)
- [Website](https://www.helius.dev/)
- [Plans](plans/helius-plans-pricing.yml)
- [Rate Limits](rate-limits/helius-rate-limits.yml)
- [Fin Ops](finops/helius-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
