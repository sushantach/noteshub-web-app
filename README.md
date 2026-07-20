# Python Security Scripts

A collection of practical Python utilities designed to demonstrate automation, data parsing, and network observation techniques within information security environments. This repository showcases the implementation of clean software architecture and **Object-Oriented Programming (OOP)** principles applied to defensive security workflows.

##Project Modules

### 1. Security Log Parser & Analyzer
* **Description:** A modular script that ingests raw server access logs or firewall event data to detect potential brute-force activities, unauthorized system access attempts, and anomalies.
* **Core Logic:** Implements an OOP framework using a dedicated `LogAnalyzer` class to cleanly filter, track, and aggregate high-risk indicators (e.g., repeated failed login attempts from a single source IP address).

### 2. Network Port Configuration Observer
* **Description:** A lightweight network observation script utilizing Python's native socket capabilities to scan local endpoints for active communication channels.
* **Core Logic:** Mimics the core functionality of automated discovery tools like Nmap by checking the status of essential operational ports (such as SSH, HTTP, and HTTPS) to identify exposed services.

## Key Learning Objectives & Focus
* **Security Automation:** Moving away from manual operations by building reusable scripts to parse security data quickly.
* **Object-Oriented Design:** Leveraging inheritance, encapsulation, and clean class structures to make security tooling scalable and easy to maintain.
* **Defensive Engineering:** Translating fundamental theoretical cybersecurity frameworks into functional code.
