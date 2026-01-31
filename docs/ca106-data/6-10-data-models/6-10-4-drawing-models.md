## 6.10.4 Drawing and representing data models

### Advice and recommendations

When drawing and representing data models, the diagram must clearly show **structure**, **relationships** and **meaning** using the correct features for each model type.

### Hierarchical data models

When representing a hierarchical model, diagrams should include:
- **Blocks** to represent data items or entities
- **Arrows** to show parent–child relationships
- **Labels** to identify each data item and its role

Recommendations:
i. Show a single root or top-level item  
ii. Ensure each child has only one parent  
iii. Use arrows to indicate direction from parent to child  

The diagram should clearly demonstrate a top-down structure.

!!! tip "Exam tip"
Examiners look for clear **parent–child relationships**. Missing arrows or unclear labels can limit marks.

---

### Network data models

When representing a network model, diagrams should include:
- **Blocks** to represent data items or entities
- **Arrows** to show relationships between data items
- **Labels** to describe entities and relationships

Recommendations:
i. Allow multiple relationships between data items  
ii. Clearly show interconnected links  
iii. Avoid forcing a single hierarchy  

The diagram should demonstrate many-to-many relationships where appropriate.

!!! tip "Exam tip"
To gain marks, ensure the diagram shows **multiple relationships**, not a disguised hierarchy.

---

### Relational data models

When representing a relational model, diagrams should include:
- **Tables** to represent entities
- **Rows** to represent records
- **Columns** to represent attributes
- **Labels** for tables and columns

Recommendations:
i. Use clear and meaningful table and column names  
ii. Represent relationships between tables clearly  
iii. Ensure each table shows a structured, tabular layout  

The diagram should clearly communicate how data is organised into related tables.

!!! tip "Exam tip"
Marks are awarded for showing **tables with clearly labelled columns**. Vague or unstructured diagrams reduce credit.

## 6.10.4 Drawing and representing data models (extended)

### Additional recommendations for relational data models

When representing **relational data models**, diagrams must clearly show how tables are linked through **keys** to demonstrate relationships between data.

### Representing primary keys

A **primary key** uniquely identifies each record in a table.

Recommendations:
i. Clearly identify the primary key column within each table  
ii. Use consistent notation to distinguish the primary key from other columns  
iii. Ensure each table has only one primary key  
iv. Choose a column name that reflects its identifying purpose  

The diagram should make it immediately clear which attribute uniquely identifies each record.

### Representing foreign keys

A **foreign key** creates a relationship between two tables by referencing a primary key in another table.

Recommendations:
i. Clearly show which column is the foreign key  
ii. Ensure the foreign key matches the primary key it references  
iii. Use arrows or connecting lines to show relationships between tables  
iv. Label relationships clearly to indicate how tables are linked  

Foreign keys should visually demonstrate how data is related across tables.

### Overall clarity and consistency

When representing keys:
- Use consistent symbols or formatting across the diagram
- Avoid clutter by keeping table layouts clear and readable
- Ensure relationships are unambiguous and easy to follow

Well-represented keys improve understanding of data integrity and relationships in relational models.

!!! tip "Exam tip"
Examiners expect **both primary and foreign keys to be clearly identifiable**. Marks are often lost when keys are implied but not clearly labelled or when table relationships are unclear.
