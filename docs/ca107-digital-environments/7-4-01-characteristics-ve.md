# 7.4.1![New Content](../../assets/icons/introduced.svg){ width="256" }  
New or significantly changed in this specification

## Virtual environment components

This section covers the role and characteristics of common virtual environment components, including virtual machines and hypervisors.

---

## Virtual machines (VMs)

### Role

- Software-based representations of physical computers  
- Run operating systems and applications in isolated environments  

---

### Clients

#### Virtual PC

**Characteristics**

- Emulates a desktop or client computer  

**Role**

- Provides user-level computing within a virtual environment  

---

#### Virtual switch

**Characteristics**

- Software-based network switch  

**Role**

- Connects virtual machines to each other and to physical networks  

---

#### Virtual router

**Characteristics**

- Software-based routing device  

**Role**

- Directs traffic between virtual networks and external networks  

---

### Servers

**Characteristics**

- Virtualised versions of physical servers  

**Role**

- Host services, applications, and shared resources for virtual clients  

---

## Hypervisors

Hypervisors manage and allocate physical hardware resources to virtual machines.

---

### Type 1 hypervisor

**Characteristics**

- Runs directly on physical hardware  

**Role**

- Controls hardware resources and hosts virtual machines  

**Benefits**

- High performance  
- Reduced overhead  

**Drawbacks**

- Requires dedicated hardware  
- More complex to configure  

---

### Type 2 hypervisor

**Characteristics**

- Runs on top of a host operating system  

**Role**

- Creates and manages virtual machines within an existing OS  

**Benefits**

- Easier installation  
- Suitable for development and testing  

**Drawbacks**

- Lower performance due to host OS overhead  
- Dependent on host operating system stability  

---

## Judgement

Virtual machines provide flexible, isolated environments for clients and servers, while hypervisors control access to physical resources.

Type 1 hypervisors prioritise performance and efficiency, whereas Type 2 hypervisors favour ease of deployment and accessibility. Suitability depends on:

i. performance requirements  
ii. available hardware  
iii. administrative complexity  
iv. purpose of virtualisation  

---

!!! tip "Exam tip"
    Higher marks are gained by linking **VM components** (virtual PC, switch, router, servers) to their **roles**, and by comparing **Type 1 vs Type 2 hypervisors** using benefits and drawbacks rather than listing definitions alone.
