# Project-Zet: Asynchronous Web Vulnerability Scanner

[![Python 3.8+](https://img.shields.io/badge/python-3.8+-blue.svg)](https://www.python.org/downloads/)
[![Maintenance](https://img.shields.io/badge/Maintained%3F-yes-green.svg)](https://GitHub.com/looplipop/project-zet/graphs/commit-activity)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

Project-Zet is an experimental, high-concurrency framework designed for automated web vulnerability discovery. Built specifically for bug bounty hunters and penetration testers, it focuses on identifying edge-case XSS, SQLi, and IDOR vulnerabilities with minimal false positives.

## Core Features
* **Asynchronous Engine:** Utilizes `aiohttp` and `asyncio` for rapid, non-blocking HTTP requests.
* **Modular Architecture:** Easy integration of custom scanning modules (XSS, SQLi, Open Redirect).
* **WAF Evasion:** Built-in payload obfuscation and dynamic User-Agent rotation (in development).

## Disclaimer
This project is currently in **Active Development (Pre-Release)**. The core engine is stable, but scanning modules are being heavily refactored for the upcoming v1.0 release.

## Contributing
We are currently processing a large backlog of internal feature requests. Pull requests are welcome but will be reviewed slowly until the core API stabilizes.
