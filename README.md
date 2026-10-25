# BranchOne | Network Infrastructure Homelab

HomeLab focused on **Linux administration, network services, switching, segmentation, and troubleshooting** using virtualized and physical networking equipment.

## Project Overview

BranchOne simulates a small business network using Ubuntu Server, VMware Workstation, and a managed switch.

The goal is to build a **simple, functional, and isolated network environment** to practice essential networking skills without affecting the home network.

## Lab Environment

| Component | Technology |
|---|---|
| Server | Ubuntu Server (VM) |
| Virtualization | VMware Workstation |
| Networking | Physical Managed Switch |
| Network Services | NTP, DNS, SSH, HTTP, DHCP (optional) |
| Troubleshooting | Wireshark, tcpdump |
| Security | VLANs, UFW, Network Isolation |

## Implementation Roadmap

### Phase 1 — Ubuntu Server & Network Services
- [x] Install Ubuntu Server
- [ ] Configure network interface and hostname
- [ ] Configure SSH for remote administration
- [ ] Install and configure NTP (Chrony)
- [ ] Verify DNS resolution and connectivity

### Phase 2 — VMware Bridged Networking
- [ ] Configure dedicated Ethernet bridge
- [ ] Assign static IP address
- [ ] Verify VM-to-host connectivity
- [ ] Validate home network isolation

### Phase 3 — Physical Switch Integration
- [ ] Connect switch to lab network
- [ ] Configure basic switch management
- [ ] Verify Ethernet connectivity and MAC learning

### Phase 4 — Switching & Segmentation
- [ ] Configure access ports and VLANs
- [ ] Practice 802.1Q trunking
- [ ] Test VLAN connectivity and isolation

### Phase 5 — Essential Linux Services
- [ ] Configure NTP for lab clients
- [ ] Implement local DNS
- [ ] Deploy a lightweight HTTP service
- [ ] Configure UFW firewall rules
- [ ] Test services across the lab

### Phase 6 — Packet Analysis & Troubleshooting
- [ ] Capture traffic with Wireshark / tcpdump
- [ ] Analyze ARP, ICMP, TCP, DNS, and NTP
- [ ] Troubleshoot connectivity and service issues

## Network Isolation

BranchOne will operate on a **dedicated network segment**, separate from the home LAN.

A dedicated Ethernet interface, switch configuration, and controlled routing will be used to prevent unintended communication between networks.

