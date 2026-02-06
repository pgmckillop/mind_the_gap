# 7.3.8 Four-layer TCP/IP model

This section covers the four-layer TCP/IP (Transmission Control Protocol / Internet Protocol) model, including the function and related protocols of each layer.

The TCP/IP model describes how data is transmitted across networks and forms the practical basis of modern internet communication.

Layers are ordered from **Application (top)** to **Network (bottom)**.

---

## Application layer

### Function

- Provides network services directly to applications  
- Combines the roles of the OSI application, presentation, and session layers  

### Related protocols

- HTTP  
- HTTPS  
- FTP  
- SMTP  
- DNS  

---

## Transport layer

### Function

- Provides end-to-end communication  
- Manages segmentation, flow control, and error handling  

### Related protocols

- TCP  
- UDP  

---

## Internet layer

### Function

- Handles logical addressing and routing of packets between networks  

### Related protocols

- IP  
- ICMP  

---

## Network layer

### Function

- Manages physical data transmission across network media  
- Handles framing and hardware addressing  

### Related protocols / standards

- Ethernet  
- ARP  

---

## Memory aid (mnemonic)

To remember the TCP/IP layers from **top to bottom**:

**All Tigers In Nets**

- **A**pplication  
- **T**ransport  
- **I**nternet  
- **N**etwork  

---

## Judgement

The TCP/IP model simplifies networking into four practical layers, improving implementation efficiency and interoperability. However, fewer layers mean responsibilities are less clearly separated than in the OSI model, which can reduce conceptual clarity when analysing faults or system behaviour.

Suitability depends on balancing simplicity and real-world implementation against detailed layered abstraction.

---

!!! tip "Exam tip"
    Use the mnemonic **All Tigers In Nets** to recall layer order. Marks are gained by linking **each layer to its function and protocol** (for example *Internet = IP routing*). Listing layers alone limits credit.
