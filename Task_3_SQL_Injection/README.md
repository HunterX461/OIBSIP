# Task 3: SQL Injection on DVWA (Low Security)

## Objective
To demonstrate an SQL Injection (SQLi) vulnerability on the Damn Vulnerable Web Application (DVWA) with the security level set to "Low".

## Tools Used
- **OS:** Kali Linux
- **Application:** DVWA (Docker Container)
- **Browser:** Firefox

## Execution Steps
1.  **Setup:** Accessed DVWA and set the security level to "Low".
2.  **Analysis:** The application takes a "User ID" input and returns the First Name and Surname.
3.  **Exploit:** Injected a malicious SQL payload into the input field to alter the backend query logic.

### The Payload
```sql
1' OR 1=1 #
