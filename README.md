# BUILD-A-HOME-NETWORK
# 🏠 Home Network Configuration Project

## 📋 Overview
This project demonstrates the design and configuration of a basic home network using a wireless router, wired clients, and a wireless client. The goal was to establish LAN and internet connectivity for multiple devices with proper DHCP and Wi-Fi security settings.

---

## 🧰 Tools & Devices Used
- **Cisco Packet Tracer**
- **Wireless Router**
- **Cable Modem**
- **2 PCs (Wired)**
- **1 Laptop (Wireless)**
- **Coaxial & Ethernet Cables**

---

## ⚙️ Configuration Steps

### 1. Connect Devices
- Connected coaxial cable from ISP to modem and TV via splitter.
- Connected cable modem to the router’s internet port.
- Linked both PCs to router’s LAN ports using Ethernet cables.

### 2. Configure Router
- Accessed the router GUI using the Office PC via DHCP.
- Changed the admin password and limited DHCP leases to 10.
- Enabled 2.4 GHz wireless and configured:
  - **SSID:** `MyHome`
  - **Security Mode:** WPA2-Personal
  - **Passphrase:** `MyPassPhrase1!`

### 3. Configure Clients
- Connected the laptop wirelessly using the SSID and passphrase.
- Verified DHCP-assigned IPs for all devices.
- Tested connectivity to external site (`skillsforall.srv`).

---

## 🔍 Testing & Verification
| Device        | Connection Type | IP Assignment | Internet Access |
|----------------|-----------------|----------------|----------------|
| Office PC     | Wired (Ethernet) | ✅ DHCP (192.x) | ✅ Successful |
| Bedroom PC    | Wired (Ethernet) | ✅ DHCP (192.x) | ✅ Successful |
| Laptop        | Wireless (Wi-Fi) | ✅ DHCP (192.x) | ✅ Successful |

---

## 📈 Results
- All devices connected successfully to the LAN and accessed the internet.
- DHCP server issued valid IPs to all clients.
- Wireless connection secured using WPA2-Personal.

---

## 🚀 Future Improvements
- Add guest Wi-Fi with limited access.
- Implement parental controls and MAC filtering.
- Test with IoT and smart home devices.
- Configure firewall and port forwarding rules.

---

## 🧾 Author
**heis-cyb3rski**  
Networking & Security Enthusiast | Home Lab Builder
