## Project Overview

This project demonstrates how lateral movement attacks can occur inside Docker-based microservice environments and how they can be mitigated using container security techniques such as Docker network segmentation and runtime threat detection with Falco.

## The lab environment contains multiple Docker containers including:

- Web Service
- API Service
- Database Service
- Attacker Container

## The project simulates attacker behavior such as:

- Network reconnaissance
- Port scanning
- Service discovery
- Unauthorized inter-container communication

Falco is integrated to monitor and detect suspicious runtime activities in real time.

## Objectives
- Simulate lateral movement attacks in Docker containers
- Perform reconnaissance using Nmap
- Analyze insecure container communication
- Implement Docker network segmentation
- Detect suspicious activities using Falco
- Mitigate unauthorized lateral movement

## Technologies Used
- Docker
- Docker Compose
- Falco
- Python Flask
- MySQL
- Alpine Linux
- Nmap
- WSL2 / Linux

## Expected Outcomes
- Detection of suspicious container behavior
- Restricted inter-container communication
- Prevention of lateral movement attacks
- Real-time runtime monitoring with Falco
- Improved container security visibility

## Learning Outcomes
This project helps understand:
- Docker networking
- Container security
- Runtime threat detection
- Lateral movement techniques
- Microservice isolation strategies

## Team
Subodh Pun 
Bhavesh Verma
