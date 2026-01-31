## 6.6 Structures for storing data

### 6.6.1 Role of metadata

**Metadata** is data that describes other data and provides context.

- **Role**:
  - identifies the content, format and origin of data
  - supports organisation, retrieval and management of data
- **Context provided**:
  - creation details
  - structure and format
  - usage and meaning of the data

Metadata enables data to be interpreted correctly and used effectively within digital software development.

!!! tip "Exam tip"
In exam answers, clearly link metadata to **context and meaning**. Marks are awarded for explaining *how metadata helps users or systems understand and manage data*, not just defining it.

---

### 6.6.2 File-based and directory-based structures

**File-based structures**
- **Definition**: Data stored within individual files.
- **Purpose**: To store data as single units.
- **When used**: For simple storage, portability and straightforward access.

**Directory-based structures**
- **Definition**: Data organised into folders that group related files.
- **Purpose**: To manage and organise multiple files logically.
- **When used**: Where large volumes of files need structure and efficient navigation.

These structures support data organisation at different levels of complexity.

!!! tip "Exam tip"
Examiners expect you to distinguish between **data stored in files** and **files organised in directories**, and to explain *why one is more suitable than the other* in a given context.

---

### 6.6.3 Hierarchy-based structure

**Hierarchy-based structure** organises data in parent–child relationships.

- **Purpose**:
  - to represent levels of importance or dependency
  - to support structured navigation and access
- **When used**:
  - where data naturally fits a top-down structure
  - where relationships between data items must be clear

Hierarchy-based structures support clear organisation and controlled access to data.

!!! tip "Exam tip"
For full marks, explain how **parent–child relationships** help organise data and why a hierarchical approach is suitable for certain types of data.

---

### 6.6.4 Interrelationships between storage structures and data transformation

Storage structures and data transformation are interrelated because the way data is stored affects how it can be transformed.

- File-based and directory-based structures influence:
  - ease of access
  - efficiency of processing
- Hierarchy-based structures influence:
  - how data is selected, filtered or aggregated during transformation
- Metadata supports transformation by:
  - providing context
  - enabling correct interpretation of stored data

Effective data transformation depends on selecting storage structures that support efficient access, processing and contextual understanding.

!!! tip "Exam tip"
When answering interrelationship questions, explicitly link **how data is stored** to **how it can be transformed**. Examiners look for clear cause-and-effect explanations, not separate descriptions.
