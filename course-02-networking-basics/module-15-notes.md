# TCP and UDP
## What It Covers
This module covers TCP and UDP, how clients access internet services, 
and how port numbers are used in relation to TCP and UDP.

## Key Terms
| Term | Definition |
|------|------------|
| TCP | Reliable transport protocol — arranges packets in order, uses acknowledgments, and resends lost packets. Slower but accurate. |
| UDP | Fast transport protocol — sends packets without acknowledgment or guaranteed delivery. No overhead, used when speed matters more than accuracy. |
| Port Number | A numerical identifier that tells the OS which application should receive incoming traffic |
| Overhead | Extra processing and data required to ensure reliability in TCP |

## Core Concepts
- TCP guarantees delivery through acknowledgments and retransmission of lost packets
- UDP sacrifices reliability for speed — used in video streaming, gaming, VoIP
- Both TCP and UDP use port numbers to direct traffic to the right application

## Common Ports
| Port | Protocol |
|------|----------|
| 22 | SSH |
| 53 | DNS |
| 80 | HTTP |
| 443 | HTTPS |
| 21 | FTP |
| 23 | Telnet |
| 25 | SMTP |
| 3389 | RDP |

## Practice Questions
- Q: What mechanism does TCP use to guarantee packet delivery?
- Q: When would you choose UDP over TCP?
- Q: What port does HTTPS use?

## What I Keep Getting Wrong
- Port numbers — added common ports table above for reference

