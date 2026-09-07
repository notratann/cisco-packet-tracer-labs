# DHCP Configuration on a Wireless Router

A hands-on Cisco Packet Tracer lab focused on configuring DHCP on a wireless router and verifying automatic IP address assignment and network connectivity.

## 🛠️ Lab Environment

- **Tool:** Cisco Packet Tracer
- **Network Device:** Wireless Router
- **End Devices:** 3 PCs
- **Protocol:** DHCP
- **IP Version:** IPv4

## 🎯 Objectives

- Connect three PCs to a wireless router
- Examine the router's default DHCP configuration
- Configure the router's LAN IP address
- Configure a custom DHCP address pool
- Configure clients to obtain IP addresses automatically
- Verify IP configuration using `ipconfig`
- Test network connectivity using `ping`

## ⚙️ Configuration

The wireless router was configured with the following network parameters:

| Setting | Configuration |
|---|---|
| Router LAN IP | `192.168.5.1` |
| DHCP Starting IP | `192.168.5.126` |
| Maximum DHCP Users | `75` |
| Client Configuration | DHCP / Automatic |

All three PCs were configured to obtain their IPv4 addresses automatically from the router's DHCP server.

## 🔍 Verification

The assigned IP configuration was verified on the client devices using:

```text
ipconfig
