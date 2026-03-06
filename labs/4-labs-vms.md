# Labs with VMs and Test Networks

[← Back to Labs](./README.md)

Building test networks; hands-on security labs.

## Table of Contents

- [Building test networks](#building-test-networks)
- [Hands-on security labs](#hands-on-security-labs)
- [References](#references)

---

## Building test networks

**Test networks** let you try **routing**, **services**, and **security** without affecting production. **VirtualBox** (or similar) runs **multiple VMs** (e.g. Linux, Windows); **internal** or **host-only** networks connect them. **OpenWRT** on a VM or device gives a **realistic** router (DHCP, firewall, VLANs) for **home/SOHO** labs. **Multi-VM** setups: e.g. one VM as “router,” others as “clients” and “servers,” with **static** or **DHCP** addressing. Source: edu-resources, gists (Learning Computer Security – OpenWRT, VirtualBox).

---

## Hands-on security labs

**Security labs** are **isolated** environments (VMs, VLANs, or air-gapped) where you **safely** run **attacks** and **mitigations** (e.g. ARP spoofing, DHCP starvation, Snort rules). Use **dedicated** lab NICs and **no** production networks. **Resources:** **Hack The Box**, **TryHackMe**, **OverTheWire** (CTF-style); **Security Onion** for **NSM**; **Network-Security** (BFreitas16) and **cybersecurity-networking** for **attack/mitigation** steps. See [security/4-attacks-mitigations](../security/4-attacks-mitigations.md), [security/7-nids-dos-identity](../security/7-nids-dos-identity.md). Source: CSIRT-MU edu-resources, Hamed233 Cybersecurity-Mastery-Roadmap.

---

## References

- edu-resources, gists (OpenWRT, VirtualBox labs); CSIRT-MU edu-resources; Network-Security (BFreitas16)
- [security/4-attacks-mitigations](../security/4-attacks-mitigations.md); [security/7-nids-dos-identity](../security/7-nids-dos-identity.md)
