# ITT-116-Platforms-and-Network-Technologies-LSturrup


**Institution:** Grand Canyon University
**Emphasis:** Cybersecurity | B.S. Information Technology

## Overview

Introductory networking course covering physical cabling, switching, wireless, server services, and routing using Cisco Packet Tracer. All labs were built around Canyon Woodcraft — a growing business in Phoenix, AZ — progressing from a SOHO setup to a fully routed small business network.

---

## Labs & Projects

| Folder | Topic | File Type |
|--------|-------|-----------|
| `Part-1-SOHO` | SOHO network setup, wireless client config, DHCP | `.pkt` |
| `Part-2-Patching` | Physical cabling, patch panel to switch, inter-switch connections | `.pka` |
| `Part-3-Switching` | Switch CLI config — VLANs, trunking, management interface | `.pka` |
| `Part-4-Wireless` | Access point config — SSIDs, WPA2-PSK, guest VLAN 240 | `.pka` |
| `Part-5-Server` | DHCP & DNS server config, static IP addressing | `.pka` |
| `Part-6-Routing` | Router-on-a-Stick, sub-interfaces, static/default routes | `.pka` |

---

## Skills Demonstrated

- SOHO network design and wireless client configuration
- Physical cabling and patch panel management
- VLAN creation and trunk configuration (VLANs 2, 4, 240)
- Switch management interface setup via CLI
- Wireless AP configuration (WPA2-PSK, guest SSID)
- DHCP and DNS server setup
- Router-on-a-Stick with sub-interfaces for inter-VLAN routing
- Default route and static routing configuration

---

## Network Details

| Element | Value |
|---------|-------|
| Company | Canyon Woodcraft (Phoenix, AZ) |
| DATA VLAN | VLAN 2 — 10.0.2.0/24 |
| MANAGEMENT VLAN | VLAN 4 — 10.0.4.0/24 |
| GUEST_WIFI VLAN | VLAN 240 — 10.0.240.0/24 |
| Router | PHX-RTR-01 (Router-on-a-Stick) |
| Server | PHX-SRV-01 — 10.0.2.10 (DHCP + DNS) |
| Domain | canyon.local |
| Corporate Wi-Fi | SSID: Canyon / WPA2-PSK |
| Guest Wi-Fi | SSID: Canyon_Guest / Open |

---

## Tools Used

- Cisco Packet Tracer 8.2.1
