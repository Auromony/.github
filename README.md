# Auromony

Status: In Development

Auromony is a cross-chain asset bridge between Aurora and Harmony based on [NXTP](https://github.com/connext/nxtp).

## Repositories

### Backend

* [nxtp](https://github.com/Auromony/nxtp) - Monorepo containing the source code of Contracts, Subgraphs and Router, as well as Docker Compose configurations for running the Router and NATS messaging server.

### Frontend

* [coinhippo-bridge](https://github.com/Auromony/coinhippo-bridge) - Frontend for user interactions with the bridging service.
* [connextscan](https://github.com/Auromony/connextscan) - Explorer frontend of the bridging service.
* [connextscan-lambda](https://github.com/Auromony/connextscan-lambda) - AWS APIs supporting the explorer frontend.
* [chaindata](https://github.com/Auromony/chaindata) - List of chains and assets. For sourcing crosschain assets in frontend.
