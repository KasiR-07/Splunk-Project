# Splunk-Project
This project demonstrates the use of Splunk Enterprise for monitoring and analyzing system/application logs. The goal is to collect log data, search it using SPL queries, and visualize important insights using dashboards. It also includes basic dashboard creation for better visualization of log data.

# Splunk Log Monitoring Project

## Overview
This project uses Splunk for analyzing system logs and detecting errors.

## Features
- Log monitoring
- Error detection using SPL
- Dashboard creation
- Alert configuration

## Sample SPL Query
index=main error | stats count by host

## Tools Used
- Splunk Enterprise
- Windows
