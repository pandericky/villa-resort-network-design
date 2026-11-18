Stage 0 — Initial Network Topology
1. Project Overview
Project: Villa Resort Network Infrastructure Design
Environment: Cisco Packet Tracer
Scenario: Greenfield network deployment for a fictional 12-villa resort.
Objective: Design, implement, and validate a functional resort network using CCNA-level networking concepts.
2. Business Requirements
The resort includes eight operational departments:
•	Front Office
•	Housekeeping
•	Engineering
•	Food & Beverage
•	Kitchen
•	Security
•	Sales & Marketing
•	Finance
The network must support internal staff operations, shared services, and guest internet access.
Guest traffic must be isolated from the internal hotel network.
3. Proposed Architecture
The project uses a collapsed-core design with a Layer 3 switch.
Topology overview:
Internet Simulation → ISP Router → Hotel Edge Router → Layer 3 Core Switch
The core switch connects to:
•	BOH Access Switch — internal staff endpoints and printers
•	Guest Access Switch — wireless access points
•	Internal Server — simulated hotel services
4. Design Decisions
Decision 001 — Collapsed-Core Architecture
Requirement: Provide network connectivity for a small resort without unnecessary infrastructure complexity.
Decision: Use one multilayer switch to provide core/distribution functionality.
Rationale: The proposed resort is small enough that dedicated core and distribution layers are not justified for this simulation.
Trade-off: The core switch is a single point of failure, and no redundant core is implemented.
Decision 002 — BOH and Guest Separation
Requirement: Prevent guest devices from accessing internal hotel resources.
Decision: Use separate access switches and VLAN-based network segmentation, with Layer 3 access-control policies planned.
Rationale: Guest devices have a different trust level from internal operational endpoints.
Verification: Connectivity and access-control testing will be performed after configuration.
5. Implementation Status
•	Initial device placement: Completed, pending technical review.
•	Initial cabling: Completed, pending technical review.
•	VLAN configuration: Not started.
•	IP addressing: Not finalized.
•	Routing and NAT: Not started.
•	Access-control policies: Not implemented.
•	Connectivity testing: Not performed.
6. Evidence and Next Steps
Pending evidence:
•	Packet Tracer topology screenshot
•	Device inventory
•	Physical port mapping
•	Saved Packet Tracer project file
Next stage: Network Design — VLAN planning, IP addressing, subnet sizing, and access-control requirements.

