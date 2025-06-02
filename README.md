# Task-5-Capture-and-Analyze-Network-Traffic-Using-Wireshark

# Tools Used :
- WireShark
- Brave Browser ( To generate packets )
- Ping command in terminal
- Gedit for Note making

# Steps Involved :
- Step 1 : First Step is to Download and Install the Wireshark From its official site 
- Step 2 : Open the Wireshark and start capturing the eth0 or Wlan0 or something same 
- Step 3 : Browse something on browser or ping anything to cature the packets 
- Step 4 : After 1 min stop capturing and analyse the wireshark using keywords like hhtp, tcp, udp, etc to check the packets of specific ports
- Step 5 : Save the file with the proper name and extension 

# Interview Questions And Answer :

## 1️⃣ What is Wireshark used for?
- A: Wireshark is a powerful open-source network protocol analyzer. It allows you to capture and interactively browse the traffic running on a computer network, helping in troubleshooting, analysis, software and protocol development, and education.

---

## 2️⃣ What is a packet?
- A: A packet is a small segment of data transmitted over a network. It typically contains a header (with source, destination, and protocol information) and a payload (the actual data). Networks transmit data by breaking it into these smaller packets.

---

## 3️⃣ How to filter packets in Wireshark?
- A: Wireshark provides a **Display Filter** bar where you can enter filter expressions (e.g., `http`, `tcp.port == 80`, `ip.addr == 192.168.1.1`) to view only specific types of packets. Additionally, the **Capture Filter** (set before capture) allows filtering at the capture stage.

---

## 4️⃣ What is the difference between TCP and UDP?
- A:  **TCP (Transmission Control Protocol)** is connection-oriented and reliable, ensuring ordered delivery with error checking and retransmission.
- **UDP (User Datagram Protocol)** is connectionless and faster but does not guarantee delivery, order, or error correction.

---

## 5️⃣ What is a DNS query packet?
- A: A DNS query packet is a request sent by a client to a DNS server to resolve a domain name (like `google.com`) into an IP address. It typically uses **UDP port 53**.

---

## 6️⃣ How can packet capture help in troubleshooting?
- A: Packet capture allows you to see actual network traffic, identify issues like packet loss, delays, retransmissions, and understand whether problems are at the client, server, or network level.

---

## 7️⃣ What is a protocol?
- A: A protocol is a set of rules and standards that define how data is transmitted and received over a network. Examples include **HTTP**, **TCP**, **DNS**, etc.

---

## 8️⃣ Can Wireshark decrypt encrypted traffic?
- A: Wireshark can decrypt some encrypted traffic if you have the right keys (like SSL/TLS session keys) and configure it properly. Without these keys, encrypted traffic like HTTPS appears as unreadable ciphertext.

---
