# AWS EC2 Security Group Hardening Project

## Project Overview
This project demonstrates how to securely deploy an AWS EC2 instance by applying basic cloud security and access control principles. The main focus was on using **AWS Security Groups as a virtual firewall** to minimize the attack surface while still allowing necessary access.

## Objective
- Restrict administrative access to the server
- Allow public web access without exposing unnecessary ports
- Practice secure key management and SSH access

## Cloud Environment
- AWS EC2 (t2.micro – Free Tier)
- Amazon Linux
- Custom Security Group
- SSH key-based authentication

## Security Configuration
The EC2 instance was protected using a custom Security Group with the following inbound rules:

- **Port 22 (SSH):**  
  Allowed only from my personal IP address to prevent unauthorized access.

- **Port 80 (HTTP):**  
  Allowed from all sources to enable public web access.

- **All other inbound traffic:**  
  Denied by default.

This follows the **principle of least privilege**, allowing only required services.

## Implementation Steps
1. Navigated to the EC2 Dashboard in AWS
2. Created a custom Security Group
3. Configured inbound rules for SSH and HTTP
4. Generated an RSA key pair for secure access
5. Launched a t2.micro EC2 instance using the custom Security Group
6. Connected to the instance via SSH to verify access controls

## Verification
- SSH access was successful only from the authorized IP
- SSH access was blocked from unauthorized sources
- The web service was accessible over HTTP
- No unnecessary ports were exposed

## Key Takeaways
- Security Groups act as stateful firewalls in AWS
- Restricting SSH access significantly improves security
- Private key files (.pem) must be protected and never uploaded publicly
- Cloud security starts with proper network access control

## Notes
- No AWS credentials, private keys, or sensitive information are included in this repository
- IP addresses and identifiers have been sanitized where applicable

## Disclaimer
This project was created for educational purposes to demonstrate foundational cloud security concepts.
