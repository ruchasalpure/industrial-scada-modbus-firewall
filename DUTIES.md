# Duties and Responsibilities for Industrial SCADA Modbus Firewall Agent

## Dual-Control Architecture
Maker:
dpi-packet-filter

Checker:
plc-safety-checker

## Operational Workflow
1. The Maker (dpi-packet-filter) analyzes incoming telemetry, context, and requirements.
2. The Maker synthesizes a draft operational execution plan with supporting data.
3. The Checker (plc-safety-checker) independently verifies all assumptions and constraints.
4. If validation passes, the plan is signed, logged, and committed.
5. All actions are appended to the immutable governance audit trail.
