# **Network‑Based Attacks**

Network‑based attacks target **communication channels, protocols, and networked systems**, aiming to intercept, alter, disrupt, or gain unauthorized access to data flowing over a network.

---

# **Network-Based Attack Types**

### **• Man‑in‑the‑Middle (MitM)**

Interception of communications between two parties to spy, modify, or inject data.

### **• Denial of Service (DoS)**

Overwhelming a system with traffic to make it unavailable.

### **• Distributed Denial of Service (DDoS)**

DoS at massive scale using many sources (botnets).

### **• DNS Spoofing / Cache Poisoning**

Forging or manipulating DNS records to redirect users to malicious destinations.

### **• ARP Spoofing / ARP Poisoning**

Sending fake ARP messages to associate the attacker’s MAC with a victim’s IP.

### **• Traffic Sniffing / Packet Capture**

Capturing network packets to read passwords, tokens, or unencrypted data.

### **• IP Spoofing**

Forging source IP addresses to impersonate another device or hide identity.

### **• Port Scanning & Network Enumeration**

Reconnaissance to identify open ports, services, and vulnerabilities.

### **• Routing Attacks (BGP Hijacking)**

Manipulating internet routing to reroute or intercept large swaths of traffic.

### **• Session Hijacking**

Stealing session cookies or tokens to take over active sessions.

---

# 🏆 **Top 10 Biggest / Most Significant Network‑Based Attacks**

### **1. Mirai Botnet (2016)**

A massive IoT botnet launched one of the largest DDoS attacks ever, taking down major services like Dyn, causing outages for Twitter, Netflix, Reddit, and more.

### **2. GitHub DDoS Attack (2018)**

GitHub faced a record‑breaking 1.35 Tbps DDoS attack using memcached reflection.

### **3. Estonia Nation‑State DDoS Attacks (2007)**

A wave of political DDoS attacks shut down government websites, banks, and news agencies.

### **4. BGP Hijack of YouTube (2008)**

Pakistan Telecom accidentally hijacked YouTube’s BGP route, taking YouTube offline globally.

### **5. Google China (2009 – Operation Aurora)**

Attackers used network intrusion + zero‑days to penetrate Google and other major companies.

### **6. Target Data Breach – Network Lateral Movement (2013)**

After phishing a vendor, attackers pivoted across the internal network to POS systems.

### **7. SolarWinds Supply‑Chain Breach (2020)**

Attackers infiltrated SolarWinds' network, compromising downstream networks worldwide.

### **8. Cloudflare BGP Routing Incident (2019)**

Misconfigured BGP routes sent global Cloudflare traffic through a small ISP, causing massive outages.

### **9. Marriott / Starwood Breach (2018)**

Attackers leveraged long‑term network access to steal data of 500 million guests.

### **10. Colonial Pipeline (2021)**

Though initiated by credential misuse, the impact was due to network segmentation failures and lateral movement risks.

---

# ⭐ **Network Attack “Must-Know” Techniques for Cybersecurity**

### **Core Network Threat Models**

* **Spoofing** (IP, DNS, ARP)
* **Sniffing** (packet capture, passive recon)
* **Injection & Manipulation** (MitM, rogue AP)
* **Reflection & Amplification** (memcached, NTP, DNS amplifiers)
* **Lateral Movement** across subnets
* **Reconnaissance** (Nmap scans, service fingerprinting)

### **Key Attack Surfaces**

* Corporate networks
* Public Wi‑Fi
* IoT devices
* VPN concentrators
* Firewalls & routers
* DNS resolvers
* Cloud environments

---

# **Essential Tools Commonly Used (Defensive Awareness)**

*Listed for professional education and defensive understanding only.*

### **Network Recon & Scanning**

* **Nmap / Zenmap** – Port scanning and service detection
* **Masscan** – Internet‑scale scanning
* **Shodan** – Internet-exposed devices search engine

### **Packet Capture & Analysis**

* **Wireshark** – Packet analysis
* **tcpdump** – CLI network capture

### **MitM & Spoofing (Defensive Study)**

* **Ettercap** – ARP poisoning & sniffing
* **Bettercap** – Advanced network interception tool

### **DDoS / Traffic Simulation (Legitimate Testing Only)**

* **LOIC / HOIC** – Historical tools used for stress testing
* **Hping3** – Packet crafting and testing

### **Network Monitoring / Detection**

* **Suricata** – IDS/IPS
* **Snort** – Network intrusion detection
* **Zeek (Bro)** – Network visibility and behavioral analysis

---

# 🧩 **Advanced Network Attack Categories**

### **Wireless Attacks**

* Evil Twin access points
* Deauthentication attacks
* WPA handshake capture

### **Network Access Control Evasion**

* MAC spoofing
* VLAN hopping

### **Cloud & Hybrid Network Exploitation**

* Misconfigured security groups
* Compromised API endpoints
* Role assumption / privilege escalation