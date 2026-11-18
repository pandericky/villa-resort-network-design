# 01 Network Design

**Status** · Planned  
**CCNA alignment** · ITN · IPv4 addressing and subnetting. SRWE · segmentation and gateway design. ENSA · architecture considerations.

[Project README](../README.md) · [Decision records](decisions/README.md) · [Previous stage](00-initial-topology.md) · [Next stage](02-basic-configuration.md)

## Requirements and design

Define the requirements, trust boundaries, addressing plan, and design decisions for the simulated resort.

| ID | Preliminary requirement | Acceptance basis | Status |
| --- | --- | --- | --- |
| REQ-01 | Separate guest Wi-Fi from back-of-house (BOH) systems. | TODO: Approve the traffic policy and verify allowed and denied paths. | Planned |
| REQ-02 | Represent staff connectivity and guest wireless access in the resort layout. | TODO: Confirm included departments, placement, and representative endpoints. | Planned |
| REQ-03 | Demonstrate reachability from authorized clients to a simulated upstream destination. | TODO: Approve source segments, destination, and expected reachability. | Planned |

### Preliminary architecture

- The planning discussion considered one simulated ISP, separate BOH and guest routers, and a router → firewall → core → distribution/access layout. TODO: Confirm device counts, firewall placement and role, and whether any network devices are shared.
- The guest layout considered access points near villa or room areas, with BOH access serving staff workstations. TODO: Confirm distribution, locations, and physical coverage assumptions.
- The staff inventory under consideration includes Front Office, Housekeeping, Engineering, Food & Beverage, Kitchen, Security, Sales & Marketing, and Finance. TODO: Confirm scope and whether any departments share a segment.

### Design records

- TODO: Record expected endpoint counts, device and simulator constraints, and any growth assumptions.
- TODO: Approve VLAN purposes, VLAN IDs, prefixes, gateways, address reservations, and WAN transit networks. Publish the approved VLAN and addressing plan here.
- TODO: Compare single versus separate routing devices and shared versus separate switching where applicable. Record the selected design, rationale, trade-offs, and dependencies in an [ADR](decisions/README.md).
- TODO: Confirm the traffic policy with [Guest Security](08-guest-security.md) and the upstream model with [WAN Routing](06-wan-routing.md).

## Implementation

TODO: Record the project revision that reflects an approved design and document any deviations from it.

## Verification

TODO: Review subnet boundaries, capacity, overlapping ranges, traffic policy, and device capabilities. Link operational tests once executed.

## Evidence and open issues

TODO: Link source artifacts, associate them with the relevant project revision, and record any observed issues.
