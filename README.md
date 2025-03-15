# SOC-in-a-Box

## Project Overview

This repository documents my SOC-in-a-Box setup using Kali Purple, Elastic Stack (Elasticsearch + Kibana), OPNSense Firewall, and Elastic Defend EDR on Windows hosts for malware detection and endpoint monitoring.

### Features:
- Centralized log management using Elastic Stack.
- Real-time endpoint monitoring with Elastic Defend for Endpoint (EDR).
- OPNSense firewall integration for network traffic analysis.

### Setup Process:
1. Installed Elastic Stack on Kali Purple for centralized log collection and analysis.
2. Configured OPNSense firewall to forward logs to Elasticsearch.
3. Deployed Elastic Agent on Windows hosts for system monitoring and malware detection.

### Challenges Faced:
1️⃣ Fixed DNS resolution issues on Kali Linux by updating /etc/resolv.conf.
2️⃣ Resolved https issues with self-signed certificates.
3️⃣ Tested EDR capabilities by simulating payload attacks like reverse shell with msfvenom.

### Screenshots:
#### Network Architecture
![Architecture Diagram](https://github.com/user-attachments/assets/9ee99b1b-d3c7-4edf-afe6-318155bf0bd4)

#### Logs Dashboard
![Logs](https://github.com/user-attachments/assets/1ff8e983-cd40-4ba5-9172-366b39bc1df1)
![Logs-Map](https://github.com/user-attachments/assets/d6195a1e-382e-4252-87d7-4fedaf416a28)

#### Overview EDR Agents
![Overview-EDR](https://github.com/user-attachments/assets/fa3028bc-94f4-4abf-807b-13fea1957282)

#### Firewall Dashboard pfSense
![Firewall-Dashboard](https://github.com/user-attachments/assets/002cbaf0-5505-4d5d-a445-49cf615c7b79)
![Firewall-Dashboard-2](https://github.com/user-attachments/assets/48c3eec7-864f-44ea-898d-4b005c1a183f)
![Firewall-Dashboard-3](https://github.com/user-attachments/assets/f8efc006-b87b-464e-9675-adf74e570659)

#### Elastic Defend Alerts
![Elastic Defend EDR](https://github.com/user-attachments/assets/f764c92d-7c18-4e8e-87a2-45fb835dec8c)

#### Logon Dashboard
![Logon Dashboard](https://github.com/user-attachments/assets/2bcb7a79-0066-4863-a289-bb49dd99d907)
![Logon Dashboard-2](https://github.com/user-attachments/assets/23b8889b-5a63-4dce-9852-da82eb849133)

#### DHCP Dashboard
![DHCP-Dashboard](https://github.com/user-attachments/assets/3352fc7c-e92a-4e5a-9a63-ef17ec7751e8)
![DHCP-Dashboard-2](https://github.com/user-attachments/assets/df1da004-c83b-469d-8178-7cafd7f2f535)

#### OPNSense Dashboard
![OPNsense-Firewall-Dashboard](https://github.com/user-attachments/assets/0db67338-0dbe-4d0a-a3ae-51ca9b2aa077)

---

## License

This project is licensed under [MIT License](LICENSE).
