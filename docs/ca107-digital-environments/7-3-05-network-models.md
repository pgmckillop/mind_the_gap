# 7.3.5

![New Content](../../assets/icons/introduced.svg){ width="256" }  
New or significantly changed in this specification

## Network models

This section covers the features, benefits, and drawbacks of common network models.

---

## Client–server

### Features

- Central server provides services and resources  
- Client devices request access from the server  
- Centralised control of users and data  

### Benefits

- Centralised management and security  
- Easier backup and maintenance  
- Consistent access to shared resources  

### Drawbacks

- Server represents a single point of failure  
- Higher setup and hardware costs  
- Requires specialist administration  

---

## Thin client

### Features

- Processing occurs mainly on a central server  
- Client devices have limited local capability  

### Benefits

- Lower client hardware requirements  
- Centralised updates and maintenance  
- Improved control over data and applications  

### Drawbacks

- Heavy dependence on server performance and network availability  
- Limited functionality if connectivity is lost  

---

## Peer-to-peer

### Features

- Devices act as both clients and servers  
- No central server  

### Benefits

- Simple and low-cost setup  
- No dedicated server hardware required  

### Drawbacks

- Limited security and management  
- Poor scalability  
- Difficult to maintain consistency across devices  

---

## Judgement

Selection of a network model depends on:

i. scale of users  
ii. need for centralised control  
iii. hardware and administration resources  
iv. tolerance for single points of failure  
v. performance and availability requirements  

Client–server and thin client models support centralised management but introduce server dependency. Peer-to-peer offers simplicity but lacks scalability and control. Suitability requires balancing cost, control, reliability, and administrative overhead.

---

!!! tip "Exam tip"
    Marks are awarded for explaining **features** and weighing **benefits against drawbacks** for each model. Higher credit is gained by justifying suitability (for example centralised control versus simplicity), not just naming the models.
