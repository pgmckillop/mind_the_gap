# 8.3.2

![New Content](../../assets/icons/introduced.svg){ width="256" }
New or significantly changed in this specification

## Understand the processes and procedures that assure internet security and the reasons why they are used

This section covers key operational processes used to protect internet-connected systems, focusing on firewall configuration, network segregation, network monitoring and port scanning.

---

## Firewall configuration

Includes:

- rules for traffic (inbound and outbound)  
- traffic type rules  
- application rules  
- IP address rules  

### Features / Characteristics / Role

- Controls which data is allowed to enter or leave a network  
- Filters traffic based on direction, protocol, application and source or destination address  
- Forms a primary boundary between internal systems and external networks  

### Benefits

- Prevents unauthorised connections  
- Reduces exposure to known attack vectors  
- Supports enforcement of organisational security policies  

### Drawbacks

- Misconfiguration can create security gaps  
- Requires continuous maintenance as services change  
- Can block legitimate traffic if rules are overly restrictive  

---

## Network segregation

Includes:

- virtual  
- physical  
- offline network  

### Features / Characteristics / Role

- Separates systems into distinct network zones  
- Limits communication between segments unless explicitly permitted  
- Offline networks provide complete isolation from external access  

### Benefits

- Restricts lateral movement during breaches  
- Protects critical systems from less secure areas  
- Reduces overall attack surface  

### Drawbacks

- Increases infrastructure complexity  
- Can reduce system interoperability  
- Adds management and configuration overhead  

---

## Network monitoring

### Features / Characteristics / Role

- Observes network traffic and system behaviour in real time  
- Detects anomalies, suspicious activity and policy violations  

### Benefits

- Enables early identification of attacks  
- Supports incident investigation and response  
- Improves visibility of system performance and security events  

### Drawbacks

- Generates large volumes of data  
- Requires skilled analysis  
- False positives can increase workload  

---

## Port scanning

### Features / Characteristics / Role

- Identifies open or exposed network ports  
- Highlights services that may be vulnerable or unnecessary  

### Benefits

- Supports proactive identification of weaknesses  
- Helps verify firewall and segmentation effectiveness  

### Drawbacks

- Requires technical expertise to interpret results  
- Can disrupt services if poorly executed  

---

## Judgement

Suitability of internet security processes depends on:

i. system criticality and exposure to external networks  
ii. organisational constraints such as staffing, skills and monitoring capacity  
iii. required balance between accessibility and protection  

Firewall rules provide essential perimeter control, network segregation limits breach impact, monitoring supports detection, and port scanning identifies weaknesses. Together these measures form layered protection. While they increase administrative and technical overhead, they significantly reduce the likelihood and scale of compromise when aligned with operational risk.

---

!!! tip "Exam tip"
    Avoid listing controls without purpose. Marks are awarded for linking *process → risk reduced → organisational benefit*. Where multiple measures are used, explain how they work together to improve security rather than describing each in isolation.
