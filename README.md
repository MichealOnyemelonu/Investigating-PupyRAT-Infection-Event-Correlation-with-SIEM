# PupyRAT Detection and Response Using SIEM

## Overview
This project demonstrates the detection of PupyRAT malware infection and how a Security Information and Event Management (SIEM) system can be used to correlate logs and generate alerts for such incidents. It includes sample SIEM rules, log files, and a comprehensive incident response process.

## Objectives
- Detect PupyRAT infection using SIEM.
- Correlate logs and create detection rules.
- Document an incident response process for malware infections.

## Technologies Used
- ELK Stack (Elasticsearch, Logstash, Kibana)
- Wazuh for log correlation
- PupyRAT malware analysis

## Contents
1. **SIEM-Rules/**: Contains correlation rules for detecting PupyRAT.
2. **Logs/**: Sample log data of a PupyRAT infection.
3. **Visualization/**: Dashboards for visualizing detected incidents in the SIEM.
4. **Incident-Response.md**: Detailed incident response steps.
5. **Report.pdf**: Final report on the PupyRAT investigation.

## How to Use
1. Set up an ELK Stack or Wazuh SIEM environment.
2. Use the provided `pupyrat-detection.conf` rules to correlate logs.
3. Ingest the provided `pupyrat-sample-logs.log` into your SIEM for testing.
4. Visualize the results using Kibana and respond to the alerts using the incident response plan.

