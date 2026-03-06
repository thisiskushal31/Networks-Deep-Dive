# Advanced & Edge Topics

Topics that build on foundations, transport, and services. Each topic has a dedicated file for full-depth content.

## Topics

### [1. Replacing TCP for datacenters](./1-replacing-tcp-datacenters.md)

Why TCP can be suboptimal in DC (Part 1); QUIC and alternatives (Part 2); deployment and migration (Part 3).

### [2. Resource limits & failure modes](./2-resource-limits-failure-modes.md)

Running out of TCP source ports; Postgres failure caused by a Cisco router (TCP case study).

### [3. TLS extensions & performance](./3-tls-extensions.md)

TLS 0-RTT (early data, replay risks, when to use).

### [4. On-premises & enterprise networking](./4-on-premises-enterprise.md)

Building a network with enterprise devices; Cisco switches, IOS, routers; console connection; troubleshooting; Packet Tracer and simulation.

### [5. Wireless & special networks](./5-wireless-special-networks.md)

Wi-Fi standards, Bluetooth, generations of wireless (1G–5G), 6G (emerging), WLAN, Zigbee.

## Learning path

1. After [foundations/](../foundations/README.md), [transport/](../transport/README.md), and [services/](../services/README.md): [Replacing TCP](./1-replacing-tcp-datacenters.md) → [Resource limits](./2-resource-limits-failure-modes.md) → [TLS 0-RTT](./3-tls-extensions.md) → [On-prem & enterprise](./4-on-premises-enterprise.md) → [Wireless](./5-wireless-special-networks.md)

## Cross-references

- **Transport:** TCP behavior, congestion control, connection states — [transport/](../transport/README.md)
- **Security:** TLS/mTLS, SNI — [security/](../security/README.md)
- **Services:** Proxies, load balancing, connection pooling — [services/](../services/README.md)
