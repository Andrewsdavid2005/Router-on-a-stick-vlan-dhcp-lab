# 🚀 Router-on-a-Stick VLAN & DHCP Lab

A hands-on Cisco Packet Tracer project demonstrating **VLAN segmentation, 802.1Q trunking, Router-on-a-Stick inter-VLAN routing, DHCP configuration, and basic network troubleshooting**.

---

## 📌 Project Overview

This project simulates a small enterprise network with two departments:

- **HR Department – VLAN 10**
- **IT Department – VLAN 20**

A Cisco router performs **inter-VLAN routing** using the Router-on-a-Stick method, while DHCP automatically assigns IP addresses to devices in each VLAN.

The project also includes basic troubleshooting scenarios to understand how network engineers identify and resolve connectivity problems.

---

## 🎯 Objectives

The main objectives of this project are:

- Configure VLANs on a Cisco switch
- Configure access ports
- Configure trunk ports
- Understand **802.1Q VLAN tagging**
- Configure Router-on-a-Stick
- Implement inter-VLAN routing
- Configure DHCP
- Configure default gateways
- Test network connectivity
- Perform basic network troubleshooting
- Verify configurations using Cisco IOS commands

---

## 🏗️ Network Topology

```text
                    ┌──────────────┐
                    │   R1 Router  │
                    │  Cisco 2911  │
                    └───────┬──────┘
                            │
                         Trunk
                            │
                    ┌───────┴──────┐
                    │     SW1      │
                    │ Cisco 2960   │
                    └──────┬───────┘
                         /     \
                        /       \
                     PC1         PC2
                    HR VLAN     IT VLAN
                      10          20
