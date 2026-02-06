# 7.3.7 Seven-layer OSI model

This section covers the seven-layer OSI (Open Systems Interconnection) model, including the function and related protocols of each layer.

The OSI model is a conceptual framework used to describe how data moves from one device to another across a network.

Layers are ordered from **Layer 7 (Application)** down to **Layer 1 (Physical)**.

---

## Application layer (Layer 7)

### Function

- Provides network services directly to applications  
- Supports user-facing network activities  

### Related protocols

- HTTP  
- FTP  
- SMTP  
- DNS  

---

## Presentation layer (Layer 6)

### Function

- Translates data into a usable format  
- Handles encryption and compression  

### Related protocols / standards

- SSL/TLS  
- JPEG / ASCII encoding standards  

---

## Session layer (Layer 5)

### Function

- Establishes, manages, and terminates communication sessions  
- Controls dialog between devices  

### Related protocols

- NetBIOS session services  
- RPC  

---

## Transport layer (Layer 4)

### Function

- Manages end-to-end data transfer  
- Handles segmentation, flow control, and error checking  

### Related protocols

- TCP  
- UDP  

---

## Network layer (Layer 3)

### Function

- Determines routing and logical addressing  
- Selects paths for data packets  

### Related protocols

- IP  
- ICMP  

---

## Data link layer (Layer 2)

### Function

- Handles node-to-node delivery  
- Manages MAC addressing and error detection on the local network  

### Related protocols / standards

- Ethernet  
- ARP  

---

## Physical layer (Layer 1)

### Function

- Transmits raw bits over physical media  
- Defines electrical, optical, and mechanical specifications  

### Related standards

- Ethernet cabling standards  
- Fibre specifications  

---

## Memory aid (mnemonic)

A commonly used mnemonic to remember the OSI layers from **Layer 7 to Layer 1**:

**All People Seem To Need Data Processing**

- **A**pplication  
- **P**resentation  
- **S**ession  
- **T**ransport  
- **N**etwork  
- **D**ata link  
- **P**hysical  

(Reverse order is also acceptable using alternatives such as:  
**Please Do Not Throw Sausage Pizza Away**.)

---

## Judgement

The OSI model provides a structured way to understand networking by separating responsibilities into layers. This supports:

i. clearer fault diagnosis  
ii. standardised design approaches  
iii. interoperability between systems  

However, it is a conceptual model rather than a direct implementation. Real networks often combine or simplify layers, so understanding requires balancing theoretical structure with practical operation.

---

!!! tip "Exam tip"
    Students frequently lose marks by listing layers without explaining **function**. Use the mnemonic **All People Seem To Need Data Processing** and always pair each layer with its **role** (for example *Transport = TCP/UDP and end-to-end delivery*). Credit is gained by linking **layer → function → protocol**, not just naming the layers.
