# SentinelShield – Intrusion Detection & Web Protection System

SentinelShield is a Python-based Intrusion Detection and Web Protection tool designed for educational and practical learning purposes.

It simulates the core behavior of a lightweight Web Application Firewall (WAF) by inspecting requests, detecting attacks, applying rate limiting, logging events, and generating alerts.

## Features
- HTTP request inspection
- Detection of SQL Injection, XSS, Command Injection, and Directory Traversal
- Rate limiting and abuse detection
- Alert generation
- Detailed security logging

## Requirements
- Python 3.x
- No external libraries required

## Usage

Normal request:
```bash
python sentinelshield.py --ip 192.168.1.10 --request "/home"
