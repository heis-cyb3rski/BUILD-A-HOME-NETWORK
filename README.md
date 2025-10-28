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
  ![image alt](https://github.com/heis-cyb3rski/BUILD-A-HOME-NETWORK/blob/60aa1bf5c64355387ce5b1d1c27c948a5b2ff231/Connected%20Devices%20with%20Cables%20STEP%201.png)

### 2. Configure Router
- Accessed the router GUI using the Office PC via DHCP.
- Changed the admin password and limited DHCP leases to 10.
- Enabled 2.4 GHz wireless and configured:
  - **SSID:** `MyHome`
  - **Security Mode:** WPA2-Personal
  - **Passphrase:** `MyPassPhrase1!`
![image alt](https://github.com/heis-cyb3rski/BUILD-A-HOME-NETWORK/blob/f685152ec2a1b457f0329b9c86c3847192d55613/configure%20Router%20through%20GUI%20.png)
![image alt](https://github.com/heis-cyb3rski/BUILD-A-HOME-NETWORK/blob/f685152ec2a1b457f0329b9c86c3847192d55613/changed%20the%20admin%20password%20.png)
![image alt](https://github.com/heis-cyb3rski/BUILD-A-HOME-NETWORK/blob/f685152ec2a1b457f0329b9c86c3847192d55613/Limited%20DHCP%20leases%20to%2010.png)
![image alt](https://github.com/heis-cyb3rski/BUILD-A-HOME-NETWORK/blob/f685152ec2a1b457f0329b9c86c3847192d55613/Enabled%202.4GHz%20Wireless%20.png)
![image alt](https://github.com/heis-cyb3rski/BUILD-A-HOME-NETWORK/blob/f685152ec2a1b457f0329b9c86c3847192d55613/Configure%20Passpharse%20Router.png)
![image alt](https://github.com/heis-cyb3rski/BUILD-A-HOME-NETWORK/blob/f685152ec2a1b457f0329b9c86c3847192d55613/Settings%20are%20successful.png)
![image alt](https://github.com/heis-cyb3rski/BUILD-A-HOME-NETWORK/blob/f685152ec2a1b457f0329b9c86c3847192d55613/Confirmation%20of%20Connectivity%20thru%20web%20browser%20on%20OFFICE%20PC%20.png)


### 3. Configure Clients
- Connected the laptop wirelessly using the SSID and passphrase.
- Verified DHCP-assigned IPs for all devices.
- Tested connectivity to external site (`skillsforall.srv`).
![image alt](https://github.com/heis-cyb3rski/BUILD-A-HOME-NETWORK/blob/f685152ec2a1b457f0329b9c86c3847192d55613/Connection%20to%20Router%20Succesful%20.png)
![image alt](https://github.com/heis-cyb3rski/BUILD-A-HOME-NETWORK/blob/f685152ec2a1b457f0329b9c86c3847192d55613/Browsing%20confirmation%20on%20Laptop.png)



---

## 🔍 Testing & Verification
| Device        | Connection Type | IP Assignment | Internet Access |
|----------------|-----------------|----------------|----------------|
| Office PC     | Wired (Ethernet) | ✅ DHCP (192.x) | ✅ Successful |
| Bedroom PC    | Wired (Ethernet) | ✅ DHCP (192.x) | ✅ Successful |
| Laptop        | Wireless (Wi-Fi) | ✅ DHCP (192.x) | ✅ Successful |

![image alt](https://github.com/heis-cyb3rski/BUILD-A-HOME-NETWORK/blob/f685152ec2a1b457f0329b9c86c3847192d55613/Completion%20of%20Activity.png)
![image alt](https://github.com/heis-cyb3rski/BUILD-A-HOME-NETWORK/blob/f685152ec2a1b457f0329b9c86c3847192d55613/Screenshot%202025-10-27%20143650.png)


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
