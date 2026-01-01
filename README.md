# Vulnerable-Webserver
# 🕶️ Intentionally Vulnerable Ubuntu Web Server – Jump Box Lab

## Overview

This repository contains an **intentionally vulnerable web application** deployed on an **Ubuntu Linux web server** running Apache and PHP. The server is designed to simulate a realistic **initial access jump box** commonly encountered during external penetration tests.

The goal of this project is to demonstrate how **web application weaknesses on a publicly reachable Linux host** can lead to system compromise and credential exposure.

> ⚠️ This application is intentionally insecure and must **only** be deployed in an isolated, controlled lab environment.

---

## Lab Description

The application runs on an Ubuntu server configured as a **public-facing web host**. From a tester’s perspective, it represents a low-hanging external target discovered during network reconnaissance.

Key characteristics:

- Ubuntu Linux
- Apache web server
- PHP-based application
- Multiple intentionally insecure endpoints
- Sensitive backup artifact exposed via application logic

The server is intended to act as a **jump box**, meaning that once compromised, it represents an attacker-controlled foothold inside the environment.

---

## Application Purpose

This project focuses on **realistic vulnerability patterns** rather than novelty exploits. The vulnerabilities mirror issues frequently observed during professional web application assessments, such as:

- Insecure handling of user input
- Unsafe file access logic
- Exposure of sensitive artifacts and credentials
- Weak separation between application logic and system resources

No exploitation instructions or payloads are provided in this repository.

---

## Learning Objectives

This lab was built to support the following learning goals:

- Understanding external attack surface exposure
- Identifying common web application vulnerabilities
- Recognizing how application-level issues can lead to host-level impact
- Evaluating the security implications of mismanaged backups and credentials
- Practicing secure code review and remediation techniques

---

## Scope & Safety

- ✔️ Designed for **local, air-gapped lab environments only**
- ✔️ Deployed on a standalone Ubuntu web server
- ✔️ No interaction with real-world infrastructure
- ❌ Do not deploy to internet-facing or production systems
- ❌ Do not reuse this code in secure applications

---

## Disclaimer

This project is intended strictly for **educational and professional portfolio purposes**.  
The author does not condone unauthorized access, misuse, or deployment of intentionally insecure systems outside of controlled lab environments.
