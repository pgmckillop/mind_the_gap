## 6.4.2 Interrelationships between structured data, unstructured data and data type

### Interrelationships

**Structured data** is data that is organised into a predefined format, such as tables with rows and columns.  
- It relies on **defined data types** to ensure consistency, accuracy and efficient processing.
- Each field in structured data is associated with a specific data type (e.g. integer, string, date), which controls how the data can be stored, validated and manipulated.

**Unstructured data** does not follow a predefined data model or structure.  
- It is not organised into fixed fields or records.
- It is commonly stored using flexible data types that can hold large or variable content, such as strings or blobs.
- Data types are applied at a broader level, rather than per field, and structure may be imposed later through transformation.

**Data types** link structured and unstructured data by determining:
- how data is stored in memory or storage
- how it can be processed and transformed
- how it can be converted between unstructured and structured forms.

Unstructured data may be **transformed into structured data** by:
i. extracting relevant elements  
ii. assigning appropriate data types  
iii. organising the data into a defined structure.

This relationship allows data to move between unstructured and structured forms while remaining usable in digital software development.

!!! tip "Exam tip"
When answering exam questions, clearly state **how data type enforces structure** in structured data and **why flexible data types are needed** for unstructured data. Examiners look for explicit links between *data structure* and *data type*, not separate descriptions.
