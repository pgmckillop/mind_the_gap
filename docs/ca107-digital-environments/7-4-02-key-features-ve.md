# 7.4.2

![New Content](../../assets/icons/introduced.svg){ width="256" }  
New or significantly changed in this specification

## Key features of virtual environments

This section covers the key features of virtual environments and how they support deployment, management, and operation of digital systems.

---

## Increased security

### Features

- Virtual machines operate in separated environments  
- Access to resources can be tightly controlled  

### Benefits

- Limits impact of failures or security breaches  
- Supports containment of compromised systems  

### Drawbacks

- Misconfiguration can still expose systems  
- Additional security layers increase management complexity  

---

## Managed execution

### Features

- Resource usage is controlled by the hypervisor  
- Virtual machines run under defined constraints  

### Benefits

- Predictable performance  
- Centralised control of workloads  

### Drawbacks

- Resource limits may reduce performance  
- Requires careful configuration  

---

## Sharing

### Features

- Multiple virtual machines use the same physical hardware  

### Benefits

- Improved utilisation of resources  
- Reduced hardware costs  

### Drawbacks

- Resource contention between virtual machines  
- Performance depends on workload balance  

---

## Aggregation

### Features

- Combines multiple physical resources into pooled virtual resources  

### Benefits

- Simplifies management  
- Supports flexible allocation of capacity  

### Drawbacks

- Added abstraction can complicate troubleshooting  
- Dependent on underlying infrastructure  

---

## Emulation

### Features

- Simulates hardware or systems in software  

### Benefits

- Supports compatibility with different platforms  
- Enables testing across environments  

### Drawbacks

- Lower performance compared with native execution  
- Increased processing overhead  

---

## Isolation

### Features

- Virtual machines operate independently of each other  

### Benefits

- Faults are contained  
- Supports secure multi-tenant environments  

### Drawbacks

- Isolation increases resource overhead  
- Requires configuration to maintain separation  

---

## Portability

### Features

- Virtual machines can be moved between hosts  

### Benefits

- Supports flexible deployment  
- Enables migration and recovery  

### Drawbacks

- Compatibility issues may arise  
- Movement can cause temporary service disruption  

---

## Judgement

Virtual environments provide flexibility, security, and efficient resource use through sharing, aggregation, and isolation. However, these benefits introduce abstraction and management overhead.

Suitability depends on:

i. security requirements  
ii. performance expectations  
iii. resource availability  
iv. operational complexity  
v. need for portability and emulation  

Balanced implementation requires weighing flexibility and efficiency against performance impact and administrative demands.

---

!!! tip "Exam tip"
    Marks are awarded for explaining **each feature** and balancing **benefits with drawbacks**. Higher credit is gained by linking features such as **isolation or portability** to real impacts on security, performance, or management rather than listing terms alone.
