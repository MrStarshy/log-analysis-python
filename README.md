# Log Analysis with Python

This repository contains a Python script that analyzes SSH login attempts in a system log file to identify possible brute-force attacks.

## Files

- `auth.log` - Sample system log file with failed and successful SSH attempts
- `log_analysis.py` - Python script that parses the log and reports suspicious IPs

## What It Does

- Extracts all failed login attempts from `auth.log`
- Uses `pandas` to count the frequency of failed IP addresses
- Outputs the top offending IPs for security review

## Built With

- Python 3
- pandas
- re (Regular Expressions)

## Author

Dika Chidume
