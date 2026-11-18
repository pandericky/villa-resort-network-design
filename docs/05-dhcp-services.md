# 05 DHCP Services

**Status** · Planned  
**CCNA alignment** · SRWE · DHCPv4 client configuration, address pools, and relay

[Project README](../README.md) · [Decision records](decisions/README.md) · [Previous stage](04-inter-vlan-routing.md) · [Next stage](06-wan-routing.md)

## Requirements and design

Define how dynamically addressed clients receive settings for each applicable segment.

- TODO: Identify DHCP clients, server placement, and whether relay is needed across routed boundaries.
- TODO: Record server alternatives, rationale, pool ranges, excluded addresses, default gateways, and DNS options where applicable.
- TODO: Check pool and reservation details against the [addressing plan](01-network-design.md).

## Implementation

TODO: Capture actual pool and relay settings, server or device identity, and sanitized lease evidence.

## Verification

TODO: Verify a representative lease on each DHCP-enabled segment. Compare the assigned address, subnet mask, gateway, and relevant options with the plan.

## Evidence and open issues

TODO: Link source artifacts, associate them with the relevant project revision, and record any observed issues.
