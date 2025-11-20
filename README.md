# EtherChannel + VLAN Trunking + Port Security

## Objective
Bundle multiple links between SW1 and SW2 using EtherChannel (LACP), configure VLAN trunking, and secure access ports with port security. Verify connectivity and security enforcement.

### Skills Learned
- Configuring EtherChannel with LACP.
- VLAN trunking configuration between switches.
- Securing access ports with port security.
- Troubleshooting switching and link aggregation issues.

### Tools Used
- Cisco switches SW1 and SW2.
- Packet Tracer for lab simulation.
- Network monitoring commands (`show etherchannel summary`, `show port-security`).

## Steps
1. Configure VLANs on both switches.
2. Bundle two physical links using LACP for EtherChannel.
3. Enable trunking on the EtherChannel interface.
4. Configure port security on access ports (limit MAC addresses, violation actions).
5. Verify EtherChannel status and VLAN trunking with `show etherchannel summary` and `show vlan brief`.
6. Test port security by connecting extra devices and checking violation logs.

*Ref 1: Network Diagram*  
![Network Diagram](imgsrc)
