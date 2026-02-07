# 8.3.1 

![New Content](../../assets/icons/introduced.svg){ width="256" }
New or significantly changed in this specification

## Understand the purposes, processes, benefits and drawbacks of common threat mitigation techniques

This section covers commonly used technical and organisational threat mitigation techniques, explaining their purpose, how they operate, and their benefits and drawbacks.

---

## Security settings (hardware and software)

### Features / Characteristics / Role

- Configure devices and applications to restrict access and behaviour  
- Control ports, services, permissions and system features  

### Benefits

- Reduces attack surface  
- Enforces organisational security policies  

### Drawbacks

- Requires ongoing management  
- Misconfiguration can introduce vulnerabilities  

---

## Anti-malware software

Includes function and actions.

### Features / Characteristics / Role

- Detects, quarantines and removes malicious software  
- Uses signature-based and behaviour-based scanning  

### Benefits

- Protects against known malware  
- Provides automated response  

### Drawbacks

- Limited effectiveness against zero-day threats  
- Can impact system performance  

---

## Intrusion detection

### Features / Characteristics / Role

- Monitors networks or systems for suspicious activity  
- Generates alerts for potential breaches  

### Benefits

- Early identification of attacks  
- Supports incident response  

### Drawbacks

- Can generate false positives  
- Requires skilled analysis  

---

## Encryption

Includes hashing, symmetric and asymmetric methods.

### Features / Characteristics / Role

- Protects data confidentiality and integrity  
- Hashing verifies data and credentials  
- Symmetric uses a shared key  
- Asymmetric uses public/private key pairs  

### Benefits

- Prevents unauthorised data access  
- Supports secure communication  

### Drawbacks

- Key management complexity  
- Processing overhead  

---

## User access policies

### Features / Characteristics /Role

- Define who can access systems and resources  
- Enforce least-privilege principles  

### Benefits

- Limits exposure of sensitive data  
- Improves accountability  

### Drawbacks

- Administrative overhead  
- Incorrect policies can block legitimate access  

---

## Staff vetting

### Features / Characteristics / Role

- Background checks before granting access  

### Benefits

- Reduces insider risk  

### Drawbacks

- Time-consuming  
- Cannot eliminate all malicious intent  

---

## Staff training

### Features / Characteristics / Role

- Improves awareness of threats and procedures  

### Benefits

- Reduces human error  
- Supports compliance  

### Drawbacks

- Requires continual reinforcement  
- Effectiveness varies between individuals  

---

## Software-based access control

### Features / Characteristics / Role

- Controls permissions through applications or operating systems  

### Benefits

- Granular control of resources  
- Centralised management  

### Drawbacks

- Dependent on correct configuration  

---

## Device hardening

### Features / Characteristics / Role

- Removes unnecessary services, ports and applications  

### Benefits

- Reduces attack vectors  

### Drawbacks

- Can reduce functionality  

---

## Backups

Includes full, incremental and differential, with safe storage.

### Features / Characteristics / Role

- Create copies of data for recovery  
- Full backs up all data  
- Incremental backs up changes since last backup  
- Differential backs up changes since last full backup  

### Benefits

- Supports recovery from data loss or ransomware  
- Improves resilience  

### Drawbacks

- Storage and management cost  
- Restoration time varies by type  

---

## Software updates

### Features / Characteristics / Role

- Apply patches to fix vulnerabilities  

### Benefits

- Reduces exposure to known exploits  

### Drawbacks

- May introduce compatibility issues  

---

## Firmware / driver updates

### Features / Characteristics / Role

- Update low-level system components  

### Benefits

- Fix hardware-related vulnerabilities  

### Drawbacks

- Risk of device instability if updates fail  

---

## Air gaps

### Features / Characteristics / Role

- Physically isolate systems from networks  

### Benefits

- Strong protection against remote attacks  

### Drawbacks

- Limits usability and integration  

---

## Certification of APIs (application programming interfaces)

### Features / Characteristics / Role

- Validates API security and compliance  

### Benefits

- Reduces risk of insecure integrations  

### Drawbacks

- Adds development overhead  

---

## VPNs (virtual private networks)

### Features / Characteristics / Role

- Encrypt traffic between remote users and networks  

### Benefits

- Protects data in transit  
- Enables secure remote access  

### Drawbacks

- Performance impact  
- Requires correct configuration  

---

## Multi-factor authentication

### Features / Characteristics / Role

- Requires multiple forms of verification  

### Benefits

- Significantly reduces credential compromise  

### Drawbacks

- Can affect usability  

---

## Password managers

### Features / Characteristics / Role

- Store and generate strong passwords  

### Benefits

- Improves password hygiene  

### Drawbacks

- Single point of failure if compromised  

---

## Port scanning

### Features / Characteristics / Role

- Identifies open or vulnerable network ports  

### Benefits

- Supports proactive security assessment  

### Drawbacks

- Requires interpretation by skilled staff  

---

## Penetration testing

Includes ethical hacking and unethical hacking.

### Features / Characteristics / Role

- Simulates attacks to identify weaknesses  

### Benefits

- Reveals real-world vulnerabilities  

### Drawbacks

- Can be costly  
- Requires specialist expertise  

---

## Judgement

Suitability of mitigation techniques depends on:

i. threat profile and system criticality  
ii. organisational constraints such as budget, skills and infrastructure  
iii. balance between usability and security overhead  

No single technique provides complete protection. Layered controls combine technical measures (encryption, access control, updates) with organisational practices (training, vetting). While stronger mitigation increases cost and complexity, it reduces the likelihood and impact of compromise.

---

!!! tip "Exam tip"
    Do not list controls in isolation. Marks are awarded for linking *technique → threat reduced → organisational impact*. Where multiple methods are used together, explain how layered security improves resilience rather than naming tools alone.
