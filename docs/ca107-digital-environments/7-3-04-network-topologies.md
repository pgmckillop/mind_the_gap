# 7.3.4

![New Content](../../assets/icons/introduced.svg){ width="256" }
New or significantly changed in this specification

## Network topologies

This section covers the features, benefits, and drawbacks of common network topologies and the distinction between logical and physical topology.

---

## Star topology

### Features

- All devices connect to a central device  
- Data passes through the central point  

### Benefits

- Easy to add or remove devices  
- Faults on individual connections do not affect the whole network  
- Centralised management  

### Drawbacks

- Central device represents a single point of failure  
- Requires more cabling than some alternatives  

---

## Mesh topology

### Features

- Devices are interconnected with multiple paths  
- Data can travel via several routes  

### Benefits

- High resilience and reliability  
- Alternative paths allow continued operation if one link fails  

### Drawbacks

- Complex to design and manage  
- Higher cost due to increased cabling and configuration  

---

## Tree topology

### Features

- Hierarchical structure combining multiple star networks  
- Uses a parent–child layout  

### Benefits

- Scalable structure  
- Supports organisation into branches or segments  

### Drawbacks

- Failure of higher-level nodes affects dependent branches  
- More complex configuration than simple topologies  

---

## Logical versus physical topology

### Logical topology

**Features**

- Describes how data flows through the network  

**Benefits**

- Helps understand communication paths  

**Drawbacks**

- May not reflect actual physical layout  

---

### Physical topology

**Features**

- Describes the physical layout of devices and cabling  

**Benefits**

- Supports installation and maintenance planning  

**Drawbacks**

- Does not show how data actually travels  

---

## Judgement

Choice of topology depends on:

i. reliability requirements  
ii. scalability needs  
iii. cost and cabling constraints  
iv. tolerance to single points of failure  
v. ease of management  

Star topologies offer simplicity, mesh provides resilience, and tree supports structured growth. Logical and physical topologies address different aspects of network design and must both be considered when evaluating suitability.

---

!!! tip "Exam tip"
    Higher marks are gained by linking each topology to its **features** and balancing **benefits against drawbacks**, for example identifying single points of failure in star or increased complexity in mesh. Answers that only name topologies limit credit.
