# 06 WAN Routing

**Status** · Planned  
**CCNA alignment** · SRWE · static and default routes. ENSA · WAN concepts and dynamic routing where in scope.

[Project README](../README.md) · [Decision records](decisions/README.md) · [Previous stage](05-dhcp-services.md) · [Next stage](07-nat-pat.md)

## Requirements and design

Define how authorized inside networks reach the simulated upstream destination and how reply traffic returns.

- TODO: Confirm the ISP representation, transit links, destination, and direction of routes.
- TODO: Compare static or default routing with a dynamic option only if both suit the topology. Record the choice and trade-offs.
- TODO: Describe the return path for the addresses visible to the upstream device, considering [NAT/PAT](07-nat-pat.md) if used.

## Implementation

TODO: Capture configured routes, relevant interfaces, packet path, and the simulated upstream endpoint.

## Verification

TODO: Check route installation, the upstream path and return traffic. A previously discussed ping to 8.8.8.8 is a candidate test only if that address is deliberately modeled in the simulation.

## Evidence and open issues

TODO: Link source artifacts, associate them with the relevant project revision, and record any observed issues.
