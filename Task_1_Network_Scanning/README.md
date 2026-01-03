# Task 1: Basic Network Scanning with Nmap

## Objective
To perform a network scan to identify open ports and services using Nmap on a target system.

## Tools Used
- **OS:** Kali Linux
- **Tool:** Nmap (Network Mapper)
- **Target:** Localhost / DVWA Container

## Execution Steps
1. **Installation:** Verified Nmap installation on the Kali Linux system.
2. **Scanning:** Executed a service version scan (`-sV`) against the target IP to map out available services.
3. **Data Collection:** Captured the output to identify open ports and the specific versions of the services running.

### The Command
```bash
nmap -sV -p 8080 127.0.0.1 -oN nmap_scan_results.txt
