# Wireshark Network Capture & Analysis

## Objective
Capture live network packets using Wireshark, identify different protocols, and summarize findings.

## Steps Followed
1. Installed Wireshark on my system.
2. Started packet capture on the active Wi-Fi network interface.
3. Generated network traffic by browsing websites and using `ping google.com`.
4. Stopped the capture after 1 minute.
5. Applied filters to view specific protocols such as HTTP, DNS, and TCP.
6. Exported the capture as a `.pcapng` file.

## Protocols Identified
- **DNS (Domain Name System)**  
  - Used for resolving domain names to IP addresses.  
  - Example: Query for `www.google.com`.

- **TCP (Transmission Control Protocol)**  
  - Reliable transport layer protocol.  
  - Example: Handshake packets during HTTP communication.

- **HTTP (Hypertext Transfer Protocol)**  
  - Used for web traffic.  
  - Example: GET request to a website.

## Outcome
- Gained hands-on experience in packet capture and filtering.
- Learned to differentiate between multiple protocols in a network stream.
- Improved awareness of how data flows across different layers of the network.

## Files in This Repo
- `capture.pcapng` → Exported packet capture file.  
- `README.md` → Documentation of steps and findings.  
- `screenshots/` → Wireshark screenshots for filtering examples.

---
