# Portfolio Boundary — MCP Server eCash

Canonical portfolio law lives in `nexacore-it/nexacore-constitution`, contract `nexacore.portfolio-execution-lock.v1`.

This repository is integration/tooling infrastructure.

It may expose bounded interfaces to eCash/ECW and approved systems, but it must not become:
- wallet balance truth;
- Meridiam authority;
- provider activation authority;
- payment/refund/settlement authority;
- a substitute for product ownership.

Connector capability is not autonomous authority. Every consequential downstream action remains subject to the owning product and authorization boundary.
