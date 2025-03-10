# 🛡️ Security Zones: Segmentation for Network Protection 🔐

## Introduction
In this section, we'll discuss a type of network security feature called a security zone. Security zones are segments of a network that protect the internal network from the internet. They are part of a security technique called network segmentation, which divides the network into segments. Each network segment has its own access permissions and security rules. 🌐

## Purpose of Security Zones 🎯
Security zones control who can access different segments of a network. They act as a barrier to internal networks, maintain privacy within corporate groups, and prevent issues from spreading to the whole network. 🛡️

### Example: Hotel Network 🏨
- **Public Wi-Fi**: Unsecured guest network.
- **Encrypted Network**: Separate network used by hotel staff.

## Subnetworks for Privacy 🏫
An organization's network can be divided into subnetworks, or subnets, to maintain privacy for each department. For instance, at a university, there may be a faculty subnet and a separate students subnet. If there is contamination on the students' subnet, network administrators can isolate it and keep the rest of the network free from contamination. 🎓

## Types of Security Zones 📊
### Uncontrolled Zone 🌍
- **Definition**: Any network outside of the organization's control, like the internet.

### Controlled Zone 🏢
- **Definition**: A subnet that protects the internal network from the uncontrolled zone.
- **Types**:
  - **Demilitarized Zone (DMZ)**: Contains public-facing services that can access the internet, such as web servers, proxy servers, DNS servers, email, and file servers. The DMZ acts as a network perimeter to the internal network.
  - **Internal Network**: Contains private servers and data that the organization needs to protect.
  - **Restricted Zone**: Protects highly confidential information that is only accessible to employees with certain privileges.

## Visualizing Security Zones 🖼️
Ideally, the DMZ is situated between two firewalls:
- **First Firewall**: Filters traffic outside the DMZ.
- **Second Firewall**: Filters traffic entering the internal network.

### Multi-layer Defense 🚧
This setup protects the internal network with several lines of defense. If there's a restricted zone, it would be protected with another firewall. Attacks that penetrate the DMZ network cannot spread to the internal network, and attacks that penetrate the internal network cannot access the restricted zone. 🔒

## Role of a Security Analyst 🕵️‍♂️
As a security analyst, you may be responsible for regulating access control policies on these firewalls. Security teams can control traffic reaching the DMZ and the internal network by restricting IPs and ports. For example, an analyst may ensure that only HTTPS traffic is allowed to access web servers in the DMZ. 🌐

## Conclusion
Security zones are an important part of securing networks, especially in large organizations. Understanding how they are used is essential for all security analysts. 🎓

Stay tuned for the next part, where we'll learn about securing internal networks! 🔍
