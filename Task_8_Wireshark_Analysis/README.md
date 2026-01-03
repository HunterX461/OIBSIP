# Task 8: Wireshark Analysis

## Objective
To capture and analyze network traffic using Wireshark to understand how data is transmitted during web interactions.

## Tools Used
- **OS:** Kali Linux
- **Tool:** Wireshark Packet Analyzer
- **Target Interface:** docker0

## Execution Steps
1. **Capture Initiation:** Launched Wireshark and selected the appropriate network interface to monitor traffic.
2. **Traffic Generation:** Interacted with the DVWA web application (performing an SQL Injection) to generate HTTP traffic.
3. **Packet Analysis:** Applied filters (e.g., `http`) to isolate the relevant request and observed the SQL payload sent in plaintext.

### Findings
By analyzing the captured HTTP GET/POST requests, I was able to verify how the application transmits user input to the backend database.

## Documentation
The packet capture data is saved as `wireshark_capture.pcap`.
