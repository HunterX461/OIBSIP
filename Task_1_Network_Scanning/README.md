# Task 1: Network Scanning

## Requirement: 
Identify open ports and services.

## Description: 
Performed a service version scan on the target system to map the attack surface.

## Command: 
nmap -sV -p 8080 127.0.0.1

### Findings: 
Identified an Apache web server running on port 8080, which hosts the DVWA application.
