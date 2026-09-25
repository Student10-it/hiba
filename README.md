# Python Security Capstone Project — End-to-End Triage & CLI Utility

## Overview
This project is an automated command-line interface (CLI) security utility and DFIR triage tool built for the Python for Security 3-Day Intensive program. It integrates network inspection, file integrity verification, and system artifact analysis.

## Features
- **File Integrity Verification:** Computes and verifies SHA-256 file hashes to detect unauthorized modifications.
- **System Triage & Monitoring:** Gathers running processes and inspects recently modified files.
- **Robust Error Handling:** Gracefully handles missing files and invalid user inputs using Python `try-except` blocks.

## How to Run
```bash
python src/main.py sample_evidence
