# SentinelScope
Advanced Web Fingerprinting & JavaScript Analysis Tool

SentinelScope is a Python-based web fingerprinting and JavaScript analysis tool designed for penetration testers and security researchers.  
It intelligently detects backend technologies, frontend frameworks, and JavaScript libraries, analyzes JavaScript files, and discovers hidden API endpoints using heuristic-based detection logic.

The tool focuses on clarity, accuracy, and human-readable output, making it suitable for real-world penetration testing, learning purposes, and professional portfolios.

---

## Features

- Backend technology detection:
  - PHP
  - Python (Django / Flask)
  - Node.js
  - Java (Spring)
  - ASP.NET

- Frontend framework & library detection:
  - React
  - Vue.js
  - Angular
  - jQuery
  - Bootstrap

- JavaScript file analysis
- Hidden API & endpoint discovery
- Optional secrets detection (API keys, JWTs, cloud keys)
- Clean and readable CLI output
- JSON export for reporting
- Heuristic-based detection (not simple string matching)

---

## Installation

### Requirements
- Python 3.8+
- pip

### Setup

```bash
git clone https://github.com/YOUR_USERNAME/SentinelScope.git
cd SentinelScope
pip install -r requirements.txt

python3 sentinelscope.py https://example.com
