### Task 7: Vulnerability Scanning with Nikto

## Objective
To use Nikto to perform a vulnerability scan on a web server and identify potential security issues.

## Tools Used
- **OS:** Kali Linux
- **Tool:** Nikto Vulnerability Scanner 
- **Target:** http://127.0.0.1:8080 (DVWA)

## Execution Steps
1. **Preparation:** Ensured the DVWA server was up and reachable via the web browser.
2. **Scanning:** Initiated a Nikto scan against the host to look for dangerous files, outdated server software, and other misconfigurations.
3. **Analysis:** Reviewed the scan report to categorize findings such as missing security headers (e.g., X-Frame-Options).

### The Command
```bash
nikto -h [http://127.0.0.1:8080] -o nikto_scan_result.txt
