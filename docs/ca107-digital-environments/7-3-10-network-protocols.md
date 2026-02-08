# 7.3.10  

![Retained](../../assets/icons/retained.svg){ width="256" }  
This content was covered in the old specification as topic(s) in 7.2.12.  
If you have access to the textbooks, you can use those resources to enhance your understanding.  

# 7.3.10 Understand the role of common network protocols

This section covers the role of common network protocols, including web, mail, routing and application protocols, and how they enable communication, data transfer and network operation.

---

## Web protocols

### HTTP  
### HTTPS  

**Features / Characteristics / Role**

- HTTP enables transfer of web resources between clients and servers  
- HTTPS extends HTTP by encrypting data in transit  
- support request–response communication models  
- underpin web applications and online services  

**Benefits**

- enable standardised web communication  
- HTTPS protects data confidentiality and integrity  
- support interoperability across platforms  

**Drawbacks**

- HTTP provides no built-in security  
- HTTPS introduces processing overhead due to encryption  
- dependent on correct certificate management  

---

## Mail protocols

### SMTP  
### POP  
### IMAP  

**Features / Characteristics / Role**

- SMTP handles sending of email between servers  
- POP downloads email from a server to a client  
- IMAP synchronises email across multiple devices  
- support storage and retrieval of electronic messages  

**Benefits**

- enable reliable electronic communication  
- IMAP supports multi-device access  
- widely supported across platforms  

**Drawbacks**

- vulnerable to spam and phishing  
- POP limits synchronisation across devices  
- require secure configuration to protect credentials  

---

## Routing protocols

### RIP  
### OSPF  

**Features / Characteristics / Role**

- determine optimal paths for data packets across networks  
- RIP uses hop count to select routes  
- OSPF uses link-state information for faster convergence  
- support dynamic network routing  

**Benefits**

- automate route selection  
- improve network resilience  
- support scalability  

**Drawbacks**

- RIP has limited scalability  
- OSPF requires greater processing and configuration  
- misconfiguration can impact network performance  

---

## Application protocols

### FTP  
### SFTP  
### DHCP  
### DNS  

**Features / Characteristics / Role**

- FTP and SFTP transfer files between systems  
- SFTP provides encrypted file transfer  
- DHCP automatically assigns IP addresses and network settings  
- DNS resolves domain names to IP addresses  

**Benefits**

- support automated network configuration  
- enable secure and efficient file transfer  
- allow human-readable addressing of network resources  

**Drawbacks**

- FTP transmits data in plain text  
- DHCP introduces dependency on central services  
- DNS failures disrupt access to network services  

---

## Judgement

Suitability of network protocols in digital environments depends on:

i. security requirements for data transmission  
ii. network size and complexity  
iii. performance and reliability expectations  
iv. administrative overhead and configuration capability  

Protocols provide essential mechanisms for communication and routing, but effectiveness is constrained by security configuration, infrastructure scale and management expertise.

---

!!! tip "Exam tip"
    Avoid listing protocols without explaining purpose. Link protocol → role → benefit/drawback → network impact. Higher marks come from comparing secure versus non-secure protocols and relating routing and application protocols to performance, reliability and administration.
