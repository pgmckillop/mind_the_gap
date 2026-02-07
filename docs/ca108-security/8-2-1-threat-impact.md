# 8.2.1

![New Content](../../assets/icons/introduced.svg){ width="256" }
New or significantly changed in this specification

## Understand potential technical threats and their impacts on organisations and individuals including prevention and mitigation methods

This section covers common technical threats to digital systems, their impacts on organisations and individuals, and the purpose of prevention and mitigation methods.

---

## Botnets

### Features / Characteristics / Role

- Networks of compromised devices controlled remotely  
- Used to launch large-scale attacks or distribute malware  

### Benefits

- None for organisations or individuals  

### Drawbacks

- Enables coordinated attacks such as DDoS  
- Consumes organisational resources  
- Can lead to data loss and service disruption  

---

## Denial of service (DoS) / distributed denial of service (DDoS)

### Features / Characteristics / Role

- Flood systems with traffic to make services unavailable  
- DDoS uses multiple sources, increasing scale and impact  

### Benefits

- None for organisations or individuals  

### Drawbacks

- Causes downtime and loss of availability  
- Disrupts business operations  
- Can lead to financial and reputational damage  

---

## Malicious hacking

Includes:

- hacktivists / nation states / organised crime / individuals  
- password cracking / brute force  
- cross-site scripting  
- SQL injection  
- buffer overflow  

### Features / Characteristics / Role

- Exploits technical weaknesses to gain unauthorised access or control  
- Targets applications, databases and operating systems  

### Benefits

- None for organisations or individuals  

### Drawbacks

- Data theft or corruption  
- System compromise  
- Potential legal, financial and reputational consequences  

---

## Malware

Includes:

- viruses  
- worms  
- key loggers  
- ransomware  
- spyware  
- remote access trojans  

### Features / Characteristics / Role

- Malicious software designed to damage, disrupt or spy on systems  
- May spread automatically or through user interaction  

### Benefits

- None for organisations or individuals  

### Drawbacks

- Loss of data and system control  
- Financial extortion (ransomware)  
- Ongoing surveillance and credential theft  

---

## Social engineering

Includes:

- phishing  
- spear phishing  
- smishing  
- vishing  
- pharming  
- watering hole attacks  
- USB baiting  

### Features / Characteristics / Role

- Manipulates users into revealing information or installing malware  
- Exploits human trust rather than technical weaknesses  

### Benefits

- None for organisations or individuals  

### Drawbacks

- Compromised credentials  
- Increased likelihood of further attacks  
- Difficult to prevent using technical controls alone  

---

## Domain name server attack / redirection of traffic

### Features / Characteristics / Role

- Redirects users to malicious sites  
- Intercepts or alters traffic routes  

### Benefits

- None for organisations or individuals  

### Drawbacks

- Credential theft  
- Exposure to malware  
- Loss of service integrity  

---

## Insecure application programming interfaces (APIs)

### Features / Characteristics / Role

- Poorly protected interfaces between systems  
- Allow unauthorised data access or manipulation  

### Benefits

- None for organisations or individuals  

### Drawbacks

- Large-scale data exposure  
- Enables automated attacks  
- Difficult to detect without monitoring  

---

## Man-in-the-middle attacks

### Features / Characteristics / Role

- Intercepts communication between two parties  
- Allows attackers to read or alter transmitted data  

### Benefits

- None for organisations or individuals  

### Drawbacks

- Loss of confidentiality and integrity  
- Credential compromise  
- Undetected data manipulation  

---

## Open / unsecured Wi-Fi networks

### Features / Characteristics / Role

- Public or poorly configured wireless access points  
- Allow attackers to observe or inject traffic  

### Benefits

- Convenience for users  

### Drawbacks

- Increased exposure to interception and spoofing  
- Higher risk of credential theft  

---

## Judgement

Suitability of prevention and mitigation depends on:

i. threat type and attack surface  
ii. organisational constraints such as budget, skills and infrastructure  
iii. required balance between usability and security  

Technical threats often combine multiple methods (for example malware delivered through social engineering). While controls such as secure configuration, monitoring and user awareness reduce risk, they introduce cost and management overhead. Effective protection requires layered mitigation aligned to operational impact and available resources.

---

!!! tip "Exam tip"
    Avoid listing threats without impact. Marks are awarded for linking *threat → effect on systems or users → organisational consequence*. Where mitigation is referenced, connect controls to the risks they reduce rather than naming tools in isolation.
