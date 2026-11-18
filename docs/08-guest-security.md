# 08 Guest Network Security

**Status** · Planned  
**CCNA alignment** · SRWE · VLAN and WLAN segmentation. ENSA · IPv4 ACLs and policy enforcement.

[Project README](../README.md) · [Decision records](decisions/README.md) · [Previous stage](07-nat-pat.md) · [Next stage](09-device-security.md)

## Requirements and design

Define the guest trust boundary and the traffic that can cross it.

- TODO: Confirm guest-to-BOH denial and document allowed upstream traffic and essential guest services.
- TODO: Specify each policy rule by source, destination, protocol or service, expected action, and enforcement point.
- TODO: Compare feasible enforcement methods. If an ACL is selected, record its order, interface and direction. Confirm which firewall capabilities are represented in Packet Tracer before documenting any firewall behavior.

## Implementation

TODO: Capture the rules and where they are applied, along with relevant simulator settings and limitations.

## Verification

TODO: Test approved guest traffic and representative guest-to-BOH traffic. Correlate a denial with policy evidence and baseline destination reachability where feasible.

## Evidence and open issues

TODO: Link source artifacts, associate them with the relevant project revision, and record any observed issues.
