# 8.4.1 
Understand how the relationships in the CIA triad interrelate

This section covers the CIA triad and explains how confidentiality, integrity and availability depend on one another to provide effective information security.

---

## Confidentiality

Includes:

- ensuring that data is kept private by controlling who has access to the data  

### Features / Characteristics / Role

- Restricts access to authorised users only  
- Prevents exposure of sensitive information  
- Forms the foundation for protecting personal and organisational data  

### Benefits

- Reduces risk of data leakage  
- Protects privacy and commercial value  
- Supports regulatory compliance  

### Drawbacks

- Over-restriction can reduce usability  
- Requires ongoing access management  

---

## Integrity

Includes:

- ensuring that the data has not been tampered with; this can be done by maintaining confidentiality  

### Features / Characteristics / Role

- Ensures data remains accurate and unaltered  
- Relies on controlled access to prevent unauthorised modification  

### Benefits

- Supports reliable decision-making  
- Maintains trust in systems and outputs  

### Drawbacks

- Requires monitoring and validation mechanisms  
- Failures may not be immediately visible  

---

## Availability

Includes:

- ensuring that data is available and useful; this can be done by ensuring integrity  

### Features / Characteristics / Role

- Ensures systems and data can be accessed when required  
- Depends on data being accurate and systems being operational  

### Benefits

- Supports continuous business operations  
- Enables timely access to information  

### Drawbacks

- Increased availability can expand attack surface  
- Requires resilience planning and resource investment  

---

## Judgement

Effectiveness of the CIA triad depends on:

i. balance between access restriction and operational usability  
ii. mechanisms to preserve data accuracy  
iii. organisational constraints such as cost, resilience planning and technical capability  

Confidentiality supports integrity by preventing unauthorised change, while integrity supports availability by ensuring data remains usable. Weakness in any element reduces the effectiveness of the others. Security controls must therefore be aligned across all three to avoid creating gaps through over-emphasis on a single component.

---

!!! tip "Exam tip"
    Do not define each element in isolation. Marks are awarded for explaining how *confidentiality supports integrity* and how *integrity supports availability*. Link the relationships, not just the individual terms.
``
