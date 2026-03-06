# Observability

Packet capture, flow visibility, QoS, security monitoring, and network operations. Each topic has a dedicated file for full-depth content.

## Topics

### [1. Signals & performance](./1-signals-performance.md)

Metrics, logs, traces; latency/jitter/loss, SLIs, synthetic checks.

### [2. Packet capture (tcpdump)](./2-packet-capture.md)

tcpdump basics, filters; SPAN, RSPAN, ERSPAN (getting traffic to your capture host); capturing IP/ARP/ICMP, UDP, TCP. See [labs/](../labs/README.md) for walkthroughs.

### [3. Wireshark](./3-wireshark.md)

Wireshark: UDP, TCP/HTTP, HTTP/2 (decrypting TLS), MongoDB, Server-Sent Events.

### [4. QoS & congestion control](./4-qos-congestion.md)

Quality of Service, token/leaky bucket, techniques, congestion control (see [transport/](../transport/README.md) for TCP).

### [5. Security monitoring & threat hunting](./5-security-monitoring.md)

Threat hunting, enterprise security monitoring, Zeek, Suricata, SIEM/ELK.

### [6. Network operations](./6-network-operations.md)

Troubleshooting methodology (identify, theory, test, plan, verify, document); network monitoring (LibreNMS, Observium, pmacct); IP SLA (active performance measurement); change management (Batfish, Oxidized); automation (NAPALM, Ansible, netmiko); model-driven programmability (NETCONF, RESTCONF, YANG, gNMI); inventory/IPAM (NetBox, phpIPAM); flow visibility (NetFlow, sFlow, IPFIX, flow records); AI/ML in network operations; incident workflows.

## Learning path

1. [Signals & performance](./1-signals-performance.md) → [Packet capture](./2-packet-capture.md) → [Wireshark](./3-wireshark.md) → [QoS](./4-qos-congestion.md) → [Security monitoring](./5-security-monitoring.md) → [Network operations](./6-network-operations.md)
2. For kernel/TCP visibility see [transport/](../transport/README.md). For step-by-step captures see [labs/](../labs/README.md).

## Cross-references

- **Transport:** TCP/UDP behavior to interpret in captures — [transport/](../transport/README.md)
- **Labs:** Step-by-step tcpdump and Wireshark walkthroughs — [labs/](../labs/README.md)
