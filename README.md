Elastic SIEM Incident Response Lab

This project documents the deployment of a fully isolated three-VM Security Operations Center (SOC) lab using the Elastic Stack.

The objective was to design and implement a centralized monitoring environment capable of ingesting, analyzing, and visualizing endpoint telemetry.

Lab Architecture

VM1 – Kali Linux (Attacker Simulation)

VM2 – Windows 10 (Target Endpoint)

VM3 – Ubuntu Monitoring Workstation

All systems were deployed within a segmented internal network (192.168.100.0/24).

Technologies Implemented

Elasticsearch (log indexing & storage)

Kibana (data visualization & analytics)

Fleet Server (centralized agent management)

Elastic Agent (endpoint telemetry collection)

Windows system metrics ingestion

Static IP network configuration

Capabilities Demonstrated

Centralized SIEM deployment

Endpoint telemetry ingestion

Real-time CPU and system metric monitoring

Secure agent enrollment via Fleet

Network segmentation for controlled attack simulation

Validation of telemetry pipeline using live system activity

Outcome

Successfully deployed a functional Elastic-based SIEM capable of:

Collecting and indexing endpoint metrics

Visualizing real-time telemetry in Kibana

Supporting future incident detection and response simulations
