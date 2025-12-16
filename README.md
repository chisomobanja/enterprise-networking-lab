# Enterprise Networking Lab (Docker-based)

## Overview
The reason I am doing this to learn enterprise level skills with limited resources. 
I wanted a way to have hands on experience working with my 8GB RAM, 4th Gen PC.
I unfortunately couldn't use tools like wazuh, security onion and many other tools as such so this is me trying to work my way around that.
All the technologies listed below use less than 4GB of ram while running simultaneously, while allowing me to practice and learn so much.


The project itself simulates a small enterprise IT environment using Docker.
It demonstrates identity management, file services, monitoring, and IT support workflows.

## Technologies Used
- Docker & Docker Compose
- OpenLDAP (Identity Management)
- Samba (File Server)
- Grafana & Loki (Monitoring and Logs)
- osTicket (Helpdesk)
- DVWA / Juice Shop (Security Testing)

## Architecture
Users authenticate via LDAP, access shared resources through Samba,
system activity is logged and visualized in Grafana, and issues are tracked using osTicket.



Ps. I will insert the architectural diagram soon, my current one needs a little fixing



## Learning Objectives
- Understand enterprise identity and access management
- Configure centralized file services
- Collect and analyze system logs
- Simulate IT support workflows
- Practice basic security incident awareness

## Status
In progress, I am actively learning and expanding
