# Auromony

Auromony is a cross-chain asset bridge between Aurora and Harmony based on [NXTP](https://github.com/connext/nxtp).

## Development Status

Prototyped: nxtp + coinhippo-bridge + chaindata (Showcase: https://www.youtube.com/watch?v=sVJhroZi2Gg)

In Development: connextscan + connextscan-lambda

## Repositories

### Backend

* [nxtp](https://github.com/Auromony/nxtp)

Monorepo containing the source code of Contracts, Subgraphs and Router, as well as Docker Compose configurations for running the Router and NATS messaging server.

* [NATS](https://github.com/Auromony/NATS)

NATS server facilitating off-chain messaging (i.e. auctioning and bidding) between frontend users and backend routers.

* [graph-node](https://github.com/Auromony/graph-node)

Local node hosting The Graph subgraphs.

* [subgraph-cache-server](https://github.com/Auromony/subgraph-cache-server)

Subgraphs caching server that provides APIs for the frontend to read subgraphs.

### Frontend

* [coinhippo-bridge](https://github.com/Auromony/coinhippo-bridge)

Frontend for user interactions with the bridging service.

* [connextscan](https://github.com/Auromony/connextscan)

Explorer frontend of the bridging service.

* [connextscan-lambda](https://github.com/Auromony/connextscan-lambda)

AWS APIs supporting the explorer frontend.

* [chaindata](https://github.com/Auromony/chaindata)

List of chains and assets. For sourcing crosschain assets in frontend.
