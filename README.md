# EOSIO (eosio)

EOSIO, now known as the Antelope protocol, is a free, open-source blockchain software protocol that provides developers and entrepreneurs with a platform on which to build, deploy, and run high-performing blockchain applications. Reference node software (nodeos) exposes HTTP/JSON RPC plugins for chain reads, history queries, transaction submission, and producer operations.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/eosio/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/eosio/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

- Antelope
- Blockchain
- EOS

## Timestamps

- **Created:** 2025-02-08
- **Modified:** 2026-05-19

## APIs

### EOSIO Nodeos Chain API

The chain_api_plugin in nodeos exposes JSON-RPC endpoints under /v1/chain for reading blockchain state, retrieving blocks and accounts, inspecting smart contract ABIs and tables, and submitting signed transactions to the network.

- **Human URL:** [https://github.com/AntelopeIO/leap](https://github.com/AntelopeIO/leap)

#### Tags

- Antelope
- Blockchain
- Chain
- JSON-RPC

#### Properties

- [OpenAPI](openapi/eosio-nodeos-chain-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/eosio-nodeos-chain-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/eosio-nodeos-chain-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [GitHub Repository](https://github.com/AntelopeIO/leap)
- [Documentation](https://developers.eos.io/)

### EOSIO Nodeos History API

The history_api_plugin exposes endpoints under /v1/history for retrieving historical actions, transactions, key accounts, and controlled accounts. On modern Antelope deployments this is typically replaced by external history solutions like Hyperion or dfuse.

- **Human URL:** [https://github.com/AntelopeIO/leap](https://github.com/AntelopeIO/leap)

#### Tags

- Antelope
- Blockchain
- History
- JSON-RPC

#### Properties

- [GitHub Repository](https://github.com/AntelopeIO/leap)
- [Documentation](https://developers.eos.io/)
- [Postman Collection](collections/eosio-nodeos-chain-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/eosio-nodeos-chain-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### EOSIO Nodeos Producer API

The producer_api_plugin exposes endpoints under /v1/producer for controlling block production on a node, including pause, resume, schedule snapshots, and manage protocol features. Restricted to operators of block producing nodes.

- **Human URL:** [https://github.com/AntelopeIO/leap](https://github.com/AntelopeIO/leap)

#### Tags

- Antelope
- Block Production
- Blockchain
- JSON-RPC

#### Properties

- [GitHub Repository](https://github.com/AntelopeIO/leap)
- [Postman Collection](collections/eosio-nodeos-chain-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/eosio-nodeos-chain-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### EOSIO Nodeos Net API

The net_api_plugin exposes endpoints under /v1/net for inspecting and managing peer-to-peer connections of an Antelope node, including connections, status, connect, and disconnect operations.

- **Human URL:** [https://github.com/AntelopeIO/leap](https://github.com/AntelopeIO/leap)

#### Tags

- Antelope
- Blockchain
- JSON-RPC
- Networking

#### Properties

- [GitHub Repository](https://github.com/AntelopeIO/leap)
- [Postman Collection](collections/eosio-nodeos-chain-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/eosio-nodeos-chain-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/eosio)
- [Website](https://eosnetwork.com/)
- [Portal](https://developers.eos.io/)
- [Getting Started](https://developers.eos.io/welcome/latest/getting-started-guide/index)
- [Tutorials](https://developers.eos.io/welcome/latest/tutorials/index)
- [Documentation](https://developers.eos.io/welcome/latest/reference/index)
- [F A Q](https://developers.eos.io/welcome/latest/faq/index)
- [GitHub Organization](https://github.com/AntelopeIO)
- [GitHub Repository](https://github.com/AntelopeIO/leap)
- [Changelog](https://github.com/AntelopeIO/leap/releases)
- [Privacy Policy](https://eos.io/legal/privacy-policy/)
- [Terms of Service](https://eos.io/legal/terms-of-use/)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
