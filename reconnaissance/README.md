# 🔎 Reconnaissance

## 📌 About

Reconnaissance is the first phase of a Vulnerability Assessment and Penetration Testing (VAPT) process.

The objective is to understand the authorized target, identify available services and technologies, and collect information that can help define the attack surface.

All reconnaissance documented in this repository is performed only against authorized laboratory environments.

---

## 🎯 Objectives

- Identify the authorized target
- Understand the application architecture
- Identify exposed services
- Identify technologies and frameworks
- Map the application's attack surface
- Document findings for further security testing

---

## 🧭 Reconnaissance Process

### 1. Scope Verification

Before testing, confirm:

- Target is explicitly authorized
- IP addresses and domains are in scope
- Testing dates and limitations are known
- Out-of-scope systems are identified

### 2. Information Gathering

Collect information such as:

- Hostnames
- IP addresses
- Open services
- Technologies
- Web application components
- Publicly exposed endpoints

### 3. Service Enumeration

Identify services exposed by the authorized target.

Examples of information to document:

| Port | Service | Version | Notes |
|---|---|---|---|
| 80 | HTTP | [Version] | Web application |
| 443 | HTTPS | [Version] | TLS enabled |
| [Port] | [Service] | [Version] | [Notes] |

### 4. Web Application Mapping

Document:

- Main pages
- Login functionality
- Authentication mechanisms
- API endpoints
- Parameters
- Forms
- Cookies
- Important application functionality

### 5. Technology Identification

Document technologies discovered during authorized testing.

Example:

```text
Web Server: [Technology]
Framework: [Technology]
Database: [Technology]
Programming Language: [Technology]
Operating System: [Technology]
