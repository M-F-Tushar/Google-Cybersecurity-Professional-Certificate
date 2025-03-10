# 🚫 Denial of Service (DoS) Attacks 💥

## Introduction
Welcome back! In this video, we're going to discuss denial of service attacks. A denial of service attack, or DoS attack, is an attack that targets a network or server and floods it with network traffic. The objective of a DoS attack is to disrupt normal business operations by overloading an organization's network. 🛡️

## Types of DoS Attacks 🚀

### 1. SYN Flood Attack 🌊
A SYN flood attack is a type of DoS attack that simulates the TCP connection and floods the server with SYN packets. 

#### Handshake Process 🤝
- **Step 1**: Device sends a SYN request to the server.
- **Step 2**: Server responds with a SYN/ACK packet and leaves a port open for the final step.
- **Step 3**: Server receives the final ACK packet from the device, establishing a TCP connection.

Malicious actors can flood the server with SYN packet requests, overwhelming the server and causing it to become unable to function. 💥

### 2. ICMP Flood Attack 🌐
An ICMP flood attack is a type of DoS attack where an attacker repeatedly sends ICMP packets to a network server, causing it to crash. ICMP stands for Internet Control Message Protocol, which is used by devices to communicate data transmission errors. 📡

### 3. Ping of Death 🪨
A ping of death attack is a type of DoS attack where a hacker sends an oversized ICMP packet (larger than 64 kilobytes) to a system, causing it to crash. This is similar to dropping a rock on a small anthill, overwhelming the system and making it unable to function. 🚨

## Distributed Denial of Service (DDoS) Attack 🌍
A distributed denial of service attack, or DDoS, is a kind of DoS attack that uses multiple devices or servers in different locations to flood the target network with unwanted traffic. The use of numerous devices makes it more likely that the total amount of traffic sent will overwhelm the target server. 💥

## Conclusion
Now that's it for DoS and DDoS attacks. Coming up, we'll continue to discuss common network attacks. Stay tuned! 🎬

