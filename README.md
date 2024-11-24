# IMEI Detection and System Information Software

## Overview

This project provides a Python-based tool to detect and gather system and network information. It is designed for analyzing device details, including hardware specifications, network data, and operating system details. Additionally, it queries network information for specific IP addresses.

---

## Features

- **System Information Retrieval**:
  - Collects detailed local system information (OS, processor, memory, disk partitions, and more).
  - Displays the data in a user-friendly format.

- **Network Information**:
  - Retrieves hostname and alias details for specified IP addresses.
  - Leverages external APIs to provide enriched geolocation and device information.

- **Data Export**:
  - Saves the gathered system information as a JSON file for easy sharing and analysis.

- **Cross-Platform**:
  - Fully compatible with Linux, macOS, and Windows systems.

---

## Prerequisites

### Required Software and Libraries

1. **Python (Version 3.10 or higher)**:
   - Ensure Python is installed. Check your version:
     ```bash
     python --version
     ```
     Download the latest version from the [official Python website](https://www.python.org/downloads/).

2. **Pip (Python Package Manager)**:
   - Typically included with Python installations. Verify installation:
     ```bash
     pip --version
     ```
   - If not installed, follow the instructions [here](https://pip.pypa.io/en/stable/installation/).

3. **Required Python Packages**:
   - Install the following dependencies:
     - `psutil` (for system information)
     - `requests` (for making HTTP requests to APIs)
     - `socket` (built-in Python library, no external installation needed)

   Install dependencies with:
   ```bash
   pip install psutil requests

