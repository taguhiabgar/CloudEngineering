# OSI (Open Systems Interconnection) model vs TCP/IP model

OSI model:
1. Physical layer
2. Data Link - Data Link layer communication needs MAC address.
3. Network - in this layer IP is the identifier
4. Transport - TCP and UDP are protocols in Layer 4. In this layer, the identifier is the port number
5. Session
6. Presentation
7. Application - SSH is 7th layer protocol

TCP/IP model:
1. Network Access (Physical and Presentation layers)
2. Internet (Network layer)
3. Transport (Transport layer)
4. Application (Session, Presentation, and Application layers)

# Server configuration architectures

configuration drift
Push architecture vs. Pull architecture

**Inbound access** refers to traffic originating outside your network attempting to enter it, while **outbound access** refers to traffic originating inside your network traveling out to the internet.

Inbound access - Connection requests originating outside your local network (e.g., the internet) and directed toward your servers or devices.

Outbound access - Connections initiated from within your local network, reaching out to external resources.

## Config management tool - Ansible

Works with push architecture model.
[docs.ansible.com](https://docs.ansible.com/)

Install ansible package - https://docs.ansible.com/projects/ansible/latest/installation_guide/intro_installation.html#installing-and-upgrading-ansible

https://docs.ansible.com/projects/ansible/latest/installation_guide/index.html

**TASK:** *rewatch video recording, find and do all the steps with Sergey*, around 1:30-2:00

TASK: Read ansible doc about aws ec2 instance

Reading: https://www.geeksforgeeks.org/linux-unix/ansible/

## Config management tool - Puppet

Works with pull (agent based) architecture model.
Is considered a bit outdated.

# DevOps configuration file formats - json, yaml, ini, xml

TASK: read about CFEngine

TASK: static inventory file vs dynamic inventory file


