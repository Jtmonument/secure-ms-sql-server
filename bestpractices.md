# SQL Server security best practices
## Questions to ask
- Which databases need encryption? / Do we need encryption?
    - Column-level protection 
    - File encryption 
- Are there records that don't need to be seen when queried?
    - Row-level protection 
- How can we assess changes in the database?
    - Auditing and reporting 
    - Data lineage and data integrity 
- How can we assign roles and permissions?
    - Identities and authentication
- Are there any vulnerabilities? / How to protect against threats?
    - Security assessment tools and evaluation 
    - Common SQL threats 
    - Infrastructure threats 
## Column-level protection
- Always Encrypted
    - Dynamic Data Masking (DDM) as an obfuscation alternative
- Randomized Encryption over Deterministic
- Always Encrypted (with enclaves)
- GRANT permissions
## Row-level protection
- Row-Level Security (RLS)
- SESSION_CONTEXT (T-SQL) for shared accounts
## File encryption
- Transparent Data Encryption
## Auditing and reporting
## Identities and authentication
## Data lineage and data integrity
- Temporal Tables
## Security assessment tools and evaluation
- Surface Area Configuration
- Vulnerability assessment for SQL Server
- SQL Data Discovery and Classification
## Common SQL threats
- ### SQL injection risks
- ### Side-channel risks
## Infrastructure threats
- ### Password risks
- ### Ransomware risks