# 7.5.3  
![Retained](../../assets/icons/retained.svg){ width="256" }  
This content was covered in the old specification as topic(s) in 7.4.2.  
If you have access to the textbooks, you can use those resources to enhance your understanding.  

# 7.5.3 Understand common cloud delivery models, their advantages and disadvantages, and the way in which responsibility and ownership of resources are distributed between the client and the cloud provider

This section covers Infrastructure as a Service (IaaS), Platform as a Service (PaaS) and Software as a Service (SaaS), including their advantages and disadvantages, how responsibility is distributed between client and provider, and how these models are used by small to medium enterprises and large organisations.

---

## Infrastructure as a Service (IaaS)

### Responsibility and ownership

**Features / Characteristics / Role**

- client manages:
  - application software  
  - system software (middleware and operating system)  
  - runtime  
  - data  
  - user accounts  
- cloud provider manages:
  - virtualisation  
  - hardware (servers, network and storage)  

This model provides configurable computing resources while retaining client responsibility for system configuration.

**Benefits**

- high flexibility and control  
- scalable infrastructure without physical hardware ownership  
- supports bespoke system architectures  

**Drawbacks**

- significant management responsibility  
- requires technical expertise  
- increased operational overhead  

---

## Platform as a Service (PaaS)

### Responsibility and ownership

**Features / Characteristics / Role**

- client manages:
  - application software  
  - data  
  - user accounts  
- cloud provider manages:
  - virtualisation  
  - hardware (servers, network and storage)  
  - system software (middleware and operating system)  
  - runtime  

This model provides a managed platform for application development and deployment.

**Benefits**

- reduced infrastructure management  
- faster deployment cycles  
- consistent development environments  

**Drawbacks**

- reduced system-level control  
- potential vendor dependency  
- platform constraints may limit customisation  

---

## Software as a Service (SaaS)

### Responsibility and ownership

**Features / Characteristics / Role**

- client manages:
  - user accounts  
  - data  
- cloud provider manages:
  - virtualisation  
  - hardware (servers, network and storage)  
  - system software (middleware and operating system)  
  - runtime  
  - application software  

This model delivers complete applications managed entirely by the provider.

**Benefits**

- minimal technical management  
- rapid implementation  
- predictable operational costs  

**Drawbacks**

- least control over configuration  
- dependency on provider availability  
- limited customisation  

---

---
## Examples to reinforce understanding
---


### Use by small to medium enterprises (SMEs)

**Features / Characteristics / Role**

- SaaS is commonly adopted to provide core business services without internal infrastructure  
- PaaS may be used to develop or host custom applications without managing operating systems or runtime environments  
- IaaS is typically used where greater control is required but physical servers are not viable  

**Benefits**

- reduced capital expenditure  
- limited need for specialist infrastructure staff  
- rapid access to scalable systems  

**Drawbacks**

- reliance on external providers  
- constrained control in SaaS and PaaS  
- ongoing subscription costs  

SMEs typically prioritise SaaS for operational simplicity, adopt PaaS for application development, and use IaaS selectively where configuration control is required.


### Use by large organisations

**Features / Characteristics / Role**

- IaaS is used to support complex, customised infrastructure and legacy integration  
- PaaS supports large-scale development teams and standardised deployment pipelines  
- SaaS provides enterprise-wide productivity and collaboration platforms  

**Benefits**

- supports global scalability  
- enables hybrid architectures  
- allows segregation of responsibilities across departments  

**Drawbacks**

- increased governance complexity  
- higher integration overhead  
- significant compliance and security management requirements  

Large organisations typically combine all three models, using IaaS for infrastructure control, PaaS for development efficiency, and SaaS for standardised services.

---

### Judgement

Suitability of cloud delivery models depends on:

i. required level of control over systems and data  
ii. organisational technical capability  
iii. cost constraints and resource availability  
iv. security, compliance and governance requirements  

IaaS offers maximum control with high management overhead, PaaS balances responsibility with development efficiency, and SaaS prioritises ease of use with minimal client ownership. SMEs tend to favour SaaS and limited PaaS adoption due to resource constraints, while large organisations typically deploy hybrid combinations to balance control, scalability and operational efficiency.

---

!!! tip "Exam tip"
    Always link each cloud model to responsibility split. For higher marks, compare SME and large organisation usage by relating control, cost and management overhead. Avoid listing models — explain suitability using ownership, security and technical capability.
