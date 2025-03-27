# Network Configuration Project

## Network Topology
- **Devices**: Router-A, Switch-A, PC-A, PC-B
- **Network**: 209.165.201.0/24
- **Subnets**:
  * LAN1: 209.165.201.0/27 (29 hosts)
  * LAN2: 209.165.201.32/28 (17 hosts)

## IP Addressing
### Router-A Interfaces
- G0/0/1 (LAN1): 209.165.201.1/27
- G0/0/0 (LAN2): 209.165.201.33/28

### Hosts
- **PC-A**:
  * IP: 209.165.201.30/27
  * Gateway: 209.165.201.1
- **PC-B**:
  * IP: 209.165.201.46/28
  * Gateway: 209.165.201.33

## Security Configurations
- Console login password: `[REDACTED]`
- Privileged EXEC secret: `[REDACTED]`
- Local user: `netadmin`
- SSH enabled with domain `netsec.com`
- Unused ports shutdown
- Password encryption enabled
- Minimum password length: 10 characters

## Key Configuration Steps
1. Network topology setup
2. IP addressing and subnetting
3. Basic device settings
4. Security hardening
5. SSH configuration

## Tools Used
- Cisco Packet Tracer
- Cisco IOS

## Notes
- Comprehensive security measures implemented
- SSH access restricted
- Management interfaces secured
