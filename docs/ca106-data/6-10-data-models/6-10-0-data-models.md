## 6.10 Data models

### 6.10.1 Types of data models

**Data models** define how data is organised into structures.

- **Hierarchical data model**:
  - Organises data in a parent–child structure.
  - Each child has a single parent.
  - Supports clear, top-down organisation.

- **Network data model**:
  - Organises data as interconnected records.
  - Data items can have multiple relationships.
  - Supports complex relationships between data items.

- **Relational data model**:
  - Organises data into tables with rows and columns.
  - Relationships are defined between tables.
  - Supports structured storage and querying of data.

!!! tip "Exam tip"
Examiners expect you to clearly describe **how each model structures data**, not just name the model.

---

### 6.10.2 Factors affecting the selection of data models

The choice of data model is influenced by:

- **Efficiency of accessing individual items of data**:
  - How quickly specific data can be retrieved.
- **Efficiency of data storage**:
  - How effectively data is stored without unnecessary duplication.
- **Level of complexity in implementation**:
  - The effort and expertise required to design, implement and maintain the model.

These factors must be balanced when selecting a data model.

!!! tip "Exam tip"
In exam questions, explicitly link **each factor** to the choice of data model to demonstrate understanding.

---

### 6.10.3 Benefits, drawbacks and suitability of data models

Different data models have benefits and drawbacks:

- **Hierarchical model**:
  - **Benefits**: simple structure, fast access along defined paths.
  - **Drawbacks**: inflexible, difficult to represent complex relationships.

- **Network model**:
  - **Benefits**: supports complex relationships.
  - **Drawbacks**: higher complexity in implementation and maintenance.

- **Relational model**:
  - **Benefits**: flexible querying, reduced data redundancy.
  - **Drawbacks**: increased complexity compared to hierarchical models.

Judgements about suitability are based on:
- efficiency of data access
- efficiency of data storage
- complexity of implementation.

The most suitable model is the one that best meets the data access and complexity requirements of the system.

!!! tip "Exam tip"
For higher marks, compare **at least two data models** and justify which is more suitable based on **efficiency and complexity**, rather than describing them individually.
