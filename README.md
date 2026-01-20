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



## Architecture Context

- PCS Architecture Docs:  
  https://github.com/khushi-org/architecture-docs
- PCS HA Gateway Design:  
  https://github.com/khushi-org/pcs-ha-gateway
- Cloud Deployment Details:  
  https://github.com/khushi-org/cloud-deployment
