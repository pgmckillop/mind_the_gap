# 7.3.9

![New Content](../../assets/icons/introduced.svg){ width="256" }
New or significantly changed in this specification

## Role of data packets in network transmission

This section covers the role of data packets in transmitting information across a network, including packet structure, packet switching, causes of packet loss, and error handling using cyclic redundancy check (CRC).

---

## Contents and structure of a data packet

### Features

A data packet is a formatted unit of data sent across a network and typically includes:

- header  
- payload (data)  
- trailer  

---

## Role of packet components

### Header

**Role**

- Contains addressing and control information  

**Benefits**

- Enables routing to the correct destination  
- Supports sequencing and identification  

**Drawbacks**

- Adds overhead to transmitted data  

---

### Payload

**Role**

- Carries the actual data being transmitted  

**Benefits**

- Delivers application information  

**Drawbacks**

- Size may be limited by network constraints  

---

### Trailer

**Role**

- Contains error-checking information  

**Benefits**

- Supports detection of transmission errors  

**Drawbacks**

- Increases packet size  

---

## Packet switching

### Features

- Data is split into packets  
- Packets may take different routes to reach the destination  

### Benefits

- Efficient use of network resources  
- Supports multiple simultaneous transmissions  

### Drawbacks

- Packets may arrive out of order  
- Some packets may be lost  

---

### Causes of packet loss

- network congestion  
- hardware failure  
- signal interference  
- buffer overflow  

---

## Error handling

### Cyclic redundancy check (CRC)

### Role

- Detects errors in transmitted packets by comparing calculated check values  

### Benefits

- Identifies corrupted packets  
- Supports reliable data transmission  

### Drawbacks

- Does not correct errors directly  
- Adds processing overhead  

---

## Judgement

Packet-based transmission enables efficient sharing of network resources and scalable communication. However, it introduces risks such as packet loss and ordering issues, requiring error detection mechanisms such as CRC.

Suitability depends on:

i. network reliability  
ii. traffic volume  
iii. tolerance to retransmission  
iv. processing overhead for error checking  

---

!!! tip "Exam tip"
    Higher marks are gained by explaining **packet structure (header, payload, trailer)** and linking **packet switching** to **packet loss and CRC error detection**. Use the sequence **split → route → check → resend** to help recall packet operation during exams.
