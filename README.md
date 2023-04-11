# Network Config

Data that is needed by the Blockchain.com clients to support different non-custodial assets.

There is one file per environment.
* prod: `config.json`
* staging: `config-staging.json`
* dev: `config-dev.json`

There's a separate service
[(service-network-config)](https://github.com/blockchain/service-network-config)
which serves these files, with some caching.
