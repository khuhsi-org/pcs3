# Failure Testing & Validation

## Objective
To validate the reliability and failover behavior of the PCS-based HA gateway.

## Test Scenarios
- Active node shutdown
- Network isolation
- Service crash

## Observations
PCS detects failures via Corosync and migrates resources automatically.

## Results
Failover occurs without user-visible disruption.
