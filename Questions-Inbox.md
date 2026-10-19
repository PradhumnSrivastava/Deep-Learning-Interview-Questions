
67. What is a semantic layer in data analytics? Ans- A semantic layer defines business-friendly meanings for data elements, metrics, and relationships, allowing users and analytical tools to interpret business concepts consistently across datasets.

68. What is a slowly changing dimension in data warehousing? Ans- A slowly changing dimension is a technique for managing changes in descriptive attributes over time. Depending on the strategy, it may overwrite old values or preserve historical versions.

69. What is the difference between a fact table and a dimension table? Ans- A fact table stores measurable business events or quantities, while a dimension table stores descriptive attributes used to categorize, filter, and analyze those facts.

70. What is the difference between a star schema and a snowflake schema? Ans- A star schema connects a central fact table directly to denormalized dimension tables, while a snowflake schema further normalizes dimensions into related tables, reducing redundancy but increasing join complexity.

71. What is a data cube in analytical processing? Ans- A data cube represents measures organized across multiple dimensions, such as sales by product, region, and time, enabling multidimensional analysis and aggregation.

72. What is OLAP, and how does it support Data Science? Ans- Online Analytical Processing (OLAP) supports multidimensional analysis of large datasets through operations such as slicing, dicing, drilling down, and aggregating business measures.

73. What is the difference between OLTP and OLAP systems? Ans- OLTP systems are optimized for frequent operational transactions, while OLAP systems are optimized for complex analytical queries over historical or aggregated data.

74. What is a data mart, and how does it differ from a data warehouse? Ans- A data mart is a focused data repository for a specific department or business domain, whereas a data warehouse generally integrates data across multiple organizational areas.

75. What is change data capture (CDC)? Ans- Change data capture identifies inserts, updates, and deletes in a source system and transfers those changes to downstream systems, helping keep analytical datasets synchronized efficiently.

76. What is the difference between synchronous and asynchronous data processing? Ans- Synchronous processing waits for an operation to complete before continuing, while asynchronous processing allows other tasks to proceed while an operation is running or awaiting completion.

77. What is idempotency in a data pipeline? Ans- Idempotency means that repeating the same operation with the same input produces the same final result without unintended duplicate effects, making pipeline retries safer and more reliable.

78. What is a data quality dimension, and which dimensions are commonly measured? Ans- A data quality dimension is a criterion used to assess data fitness for use. Common dimensions include accuracy, completeness, consistency, validity, uniqueness, and timeliness.

79. What is schema evolution in data systems? Ans- Schema evolution is the process of changing a dataset's structure over time, such as adding or modifying fields, while managing compatibility with existing producers, consumers, and stored data.

80. What is the difference between data serialization and data compression? Ans- Serialization converts structured objects into a format suitable for storage or transmission, while compression reduces the number of bytes required to represent data. A serialized format may also support compression.
