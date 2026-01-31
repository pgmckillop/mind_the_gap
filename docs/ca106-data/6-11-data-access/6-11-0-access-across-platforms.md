## 6.11 Data access across platforms

### 6.11.1 Accessing data across platforms

Accessing data across platforms requires controls and mechanisms that manage **who** can access data and **how** that access is performed.

#### Permissions

Permissions define what actions can be performed on data.

- **Authorisation**:
  - Confirms whether a user or system is allowed to access specific data.
- **Privileges**:
  - Define the level of access granted, such as read or write access.
- **Access rights**:
  - Specify exactly which data or resources can be accessed.
- **Rules**:
  - Conditions that control access, such as time, location or context.

**Purpose**:
- To protect data from unauthorised access.
- To ensure appropriate use of data.

**Benefits**:
- Improved security.
- Controlled and auditable access.

**Drawbacks**:
- Increased complexity in management.
- Risk of misconfiguration restricting valid access.

#### Access mechanisms

Access mechanisms enforce permissions across platforms.

- **Role-Based Access Control (RBAC)**:
  - Access is granted based on user roles.
  - **Benefits**: scalable and easier to manage.
  - **Drawbacks**: less flexible for individual exceptions.

- **Rule-Based Access Control (RuBAC)**:
  - Access is granted based on defined rules.
  - **Benefits**: fine-grained and context-aware control.
  - **Drawbacks**: complex to design and maintain.

- **Application Programming Interfaces (API)**:
  - Interfaces that allow systems to exchange data.
  - **Benefits**: enable interoperability between platforms.
  - **Drawbacks**: introduce security risks if poorly managed.

!!! tip "Exam tip"
For higher marks, clearly separate **permissions** from **access mechanisms** and explain how each contributes to secure cross-platform data access.

---

### 6.11.2 Benefits and drawbacks of methods to access data across platforms

Methods used to access data across platforms offer different advantages and limitations.

**Benefits**:
- Enable data sharing between systems.
- Support integration of services across platforms.
- Improve efficiency and consistency of data access.

**Drawbacks**:
- Increased security risks if access controls are weak.
- Greater complexity in configuration and maintenance.
- Potential performance overhead.

Understanding these trade-offs allows appropriate selection of access methods based on system requirements.

!!! tip "Exam tip"
In exam answers, include **both a benefit and a drawback** for at least one access method. Examiners reward balanced responses that demonstrate understanding of trade-offs.
