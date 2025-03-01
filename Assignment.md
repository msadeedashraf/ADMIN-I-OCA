### Assignment 1: Database Storage – Tablespaces vs. Datafiles vs. Segments

##### Objective: 
-   Understand the storage architecture of Oracle databases, how different components relate, and best practices for managing them.

**Tasks:**
- Explain the difference between Tablespaces, Datafiles, Segments, Extents, and Blocks in Oracle.
- Compare Permanent, Temporary, and Undo Tablespaces – when and why should each be used?
- Research how datafiles are managed – auto-extension, manual growth, and space allocation strategies.
- Analyze how improper tablespace management can affect performance and availability.
- Investigate what happens when a tablespace runs out of space and propose solutions.

**Deliverables:**
- A comparative table explaining each storage component with examples.
- A report on best practices for managing storage efficiently.

### Assignment 2: User Management and Privileges – System vs. Object Privileges

##### Objective: 
-   Learn how users, roles, and privileges are managed in Oracle and their impact on security.

**Tasks:**
- Define System Privileges and Object Privileges and explain their differences.
- Research how Roles simplify privilege management – when should roles be used instead of direct grants?
- Compare the DBA, SYSDBA, and SYSOPER roles – when should each be assigned?
- Analyze the impact of granting excessive privileges – security risks and performance concerns.
- Investigate how Oracle enforces the principle of least privilege to protect databases.

**Deliverables:**
A comparative analysis between system and object privileges.
A case study explaining a security breach caused by improper privilege assignment and how it could have been prevented.

### Assignment 3: Difference Between Logical and Physical Structures in Oracle

##### Objective: 
-   Understand the core architecture of an Oracle database and how logical structures relate to physical storage.

**Tasks:**
Explain the difference between Logical and Physical database structures in Oracle.
Compare Schemas, Tables, Indexes, and Views – what role do they play in logical organization?
Describe Data Blocks, Extents, and Segments – how do they map to physical storage?
Research how improper storage management (e.g., fragmentation, poorly designed indexes) can affect performance.
Analyze a real-world example where understanding logical vs. physical storage helped in troubleshooting performance issues.

**Deliverables:**
A diagram illustrating logical and physical structures in an Oracle database.
A technical report on how logical design choices impact storage performance.

### Assignment 4: Difference Between Shared Server and Dedicated Server Architecture

##### Objective: 
-   Compare Oracle’s Shared Server and Dedicated Server architectures and analyze their impact on performance and resource utilization.

**Tasks:**
Explain how Oracle processes client requests using both Dedicated and Shared Server modes.
Compare the pros and cons of Dedicated Server vs. Shared Server in different workloads.
Research how the Oracle Listener works in both architectures.
Investigate a real-world scenario where using Shared Server improved system performance.
Propose a decision-making guide on when to use each architecture based on business needs.

**Deliverables:**
A comparison table showing performance, scalability, and resource usage differences.
A decision-making flowchart on when to use Shared vs. Dedicated Server architecture.

### Assignment 5: Understanding Oracle Background Processes and Their Role in Database Performance

##### Objective: 
-   Learn about Oracle’s background processes, their functions, and how they affect database performance and stability.

**Tasks:**
Identify and describe the key Oracle background processes (e.g., PMON, SMON, DBWn, LGWR, CKPT).
Explain how each process contributes to database health and recovery.
Compare checkpointing (CKPT) and redo log writing (LGWR) – how do they interact?
Research how improper log writer tuning can lead to performance bottlenecks.
Investigate a real-world incident where background process failure led to database issues.

**Deliverables:**
A detailed explanation of key background processes and their functions.
A case study of an Oracle performance issue linked to a background process failure and how it was resolved.