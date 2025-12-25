# hvac-tab-automation
Python scripts for merging NEBB/AABC field reports and automating traverse calculations.
# HVAC TAB Report Automation

## Overview
A collection of Python scripts developed by **Dyami Connell** to automate Testing, Adjusting, and Balancing (TAB) field reporting. These tools are designed to eliminate manual data entry errors and streamline the generation of NEBB/AABC compliant reports.

## Features
- **Excel to PDF:** Automatically converts raw field data (`.xlsx`) into formatted PDF reports.
- **Traverse Calculation:** Validates Log-Tchebycheff and Equal Area method calculations.
- **Batch Processing:** Merges multiple zone reports into a single client deliverable.

## Requirements
- Python 3.8+
- pandas
- reportlab
- openpyxl

## Usage
1. Place raw field reports in the `/input` folder.
2. Run the script:
   ```bash
   python report_merger.py
