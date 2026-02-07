# 8.4.2

![New Content](../../assets/icons/introduced.svg){ width="256" }  
New or significantly changed in this specification

## Understand the elements of the Identification Authentication Authorisation Accountability (IAAA) model, including the techniques used and their benefits and drawbacks

This section covers the four elements of the IAAA model and how identification, authentication, authorisation and accountability work together to control access to digital systems.

---

## Identification

Includes:

- recognising the individual within a digital system  
- knowledge-based identification, including username  
- possession-based identification methods  
- biometric-based ID methods  

### Features / Characteristics / Role

- Establishes who is requesting access  
- Uses knowledge (for example usernames), possession (tokens or devices), or biometric traits  
- Provides the initial identity claim before verification  

### Benefits

- Enables individual user recognition  
- Supports personalised access and tracking  
- Forms the foundation of access control  

### Drawbacks

- Usernames alone provide weak assurance  
- Possession-based methods can be lost or stolen  
- Biometric data cannot be changed if compromised  

---

## Authentication

Includes:

- verifying the identity claimed during the identification phase  
- multi-factor authentication methods  
- passwords and passphrases  
- biometric authentication  

### Features / Characteristics / Role

- Confirms that the identified user is genuine  
- May combine multiple factors (knowledge, possession, biometric)  
- Prevents unauthorised users from impersonating others  

### Benefits

- Significantly reduces risk of account compromise when multiple factors are used  
- Strengthens protection of systems and data  

### Drawbacks

- Adds complexity and user friction  
- Password-based methods remain vulnerable to poor practice  
- Biometric systems require specialist hardware  

---

## Authorisation

Includes:

- ensuring that authenticated users can only access resources and perform actions they are permitted to  
- role-based, using the role of the user within the digital system  
- access control lists  

### Features / Characteristics / Role

- Determines what authenticated users are allowed to do  
- Applies permissions based on roles or explicit access rules  
- Enforces least-privilege principles  

### Benefits

- Limits exposure of sensitive resources  
- Reduces impact of compromised accounts  
- Supports structured permission management  

### Drawbacks

- Requires careful design and maintenance  
- Incorrect configuration can grant excessive access or block legitimate users  

---

## Accountability

Includes:

- ensuring that any actions within a system can be traced back to the responsible user  
- audit logs  
- user activity  

### Features / Characteristics / Role

- Records user actions and system events  
- Enables investigation and compliance checking  
- Supports detection of misuse or breaches  

### Benefits

- Improves traceability and responsibility  
- Acts as a deterrent to malicious behaviour  
- Supports incident response  

### Drawbacks

- Generates large volumes of data  
- Requires monitoring and secure log storage  
- Ineffective without regular review  

---

## Judgement

Effectiveness of the IAAA model depends on:

i. strength of identification and authentication mechanisms  
ii. accuracy of authorisation rules and role definitions  
iii. organisational constraints such as monitoring capability, cost and user management overhead  

Identification establishes identity, authentication verifies it, authorisation limits permitted actions, and accountability records outcomes. Weakness in any stage reduces overall security. Strong controls increase protection but also add administrative and usability overhead, requiring balance between operational efficiency and risk reduction.

---

!!! tip "Exam tip"
    Marks are awarded for linking the stages together (identify → authenticate → authorise → account). Avoid defining each element separately — explain how failure at one stage affects the others and how benefits must be weighed against usability and management overhead.
