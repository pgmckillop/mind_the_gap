## 6.11.3 Interrelationships between data access requirements and access methods

### Interrelationships and judgements

**Data access requirements** define *what level of access is needed*, *by whom* and *under what conditions*.  
**Data access methods** determine *how that access is technically implemented* across platforms.

### Interrelationships

i. **Security requirements and access methods**  
- High security requirements increase the need for controlled permissions and robust access mechanisms.
- Role-based and rule-based access controls help enforce differing security levels.
- APIs require additional controls to prevent unauthorised access.

ii. **User and system roles**  
- Different users and systems require different levels of access.
- Role-based access aligns access methods to defined responsibilities.
- Rule-based access supports conditional access across platforms.

iii. **Data sensitivity and access control**  
- Sensitive data requires stricter access requirements.
- Access methods must limit privileges and enforce authorisation.
- Less sensitive data may allow simpler access mechanisms.

iv. **Scalability and complexity**  
- Increasing numbers of users or platforms require scalable access methods.
- More complex requirements increase management and maintenance overhead.

### Making judgements about suitability

Judgements should consider:
- the sensitivity and value of the data
- the number and type of users or systems accessing the data
- security, performance and management requirements.

Accessing data across platforms is suitable when:
- access methods match the defined access requirements
- security risks are effectively controlled
- the approach remains manageable as systems scale.

Effective digital software development balances **access needs** with **security and complexity constraints**.

!!! tip "Exam tip"
For full marks, clearly link **a specific access requirement** to **a specific access method** and justify *why it is suitable*. Examiners reward explicit cause-and-effect reasoning.
