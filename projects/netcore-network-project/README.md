# Netcore Systems Network Design and Security Project

## Project Overview

This Cisco Packet Tracer case study involved designing and configuring a structured network for Netcore Systems Limited across IT, Sales, and HR departments.

## Purpose

The project focused on improving network structure, departmental communication, centralized addressing, basic services, and access control while documenting the configuration and validation steps.

## Tools Used

- Cisco Packet Tracer
- Cisco 2911 router
- Cisco 2960 switches
- PCs and server devices

## Network Design

- IT network: `192.168.10.0/24`
- IT server: `192.168.10.2/24`
- IT default gateway: `192.168.10.1`
- Centralized DHCP services hosted on the IT server
- DNS and HTTP services configured on the server
- DHCP relay configured for remote subnets using `ip helper-address 192.168.10.2`

## Security Control Implemented

An access control list was configured to block Sales traffic from pinging the IT network while allowing permitted communication elsewhere. The ACL was applied inbound on the Sales-facing router interface and validated through ping testing.

## Validation Performed

- Confirmed cross-subnet connectivity where permitted
- Confirmed Sales-to-IT ping traffic was blocked by the ACL
- Confirmed HR remained reachable where expected
- Verified centralized addressing and server services
- Tested DNS and HTTP functionality

## Skills Demonstrated

- Network topology design
- IPv4 addressing and subnet awareness
- Router and switch configuration
- DHCP and DHCP relay
- DNS and HTTP service configuration
- ACL implementation and testing
- Network troubleshooting
- Technical documentation and evidence collection

## GRC Relevance

The project demonstrates practical understanding of network segmentation, access control, least-privilege concepts, configuration validation, and evidence gathering. These are relevant to control testing, audit readiness, security governance, and documenting whether technical controls operate as intended.

## Evidence

Project evidence includes the Cisco Packet Tracer topology, configuration screenshots, connectivity tests, ACL validation, and the completed project report.
