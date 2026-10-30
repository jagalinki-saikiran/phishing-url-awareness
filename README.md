# EWB Phishing URL Awareness Checker

A simple Python-based command-line tool designed to inspect visible URL text for common phishing warning signs (such as IP addresses in hostnames, '@' symbol obfuscation, excessive subdomains, punycode, and HTTP usage).

## Features
- Text-only URL inspection (does not execute or open live web requests).
- Detects obfuscation attempts and suspicious hostname structures.
- Lightweight, relying solely on Python's standard libraries (`re` and `urllib`).

## Usage
Run the script using Python 3:
```bash
python3 phishing_checker.py