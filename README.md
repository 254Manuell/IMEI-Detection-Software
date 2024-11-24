# IMEI Detection and System Information Software

## Overview

This project provides a Python-based software tool for detecting and gathering system and network information. It is designed for individuals and organizations looking to analyze device details such as hardware specifications, network data, and operating system details. The tool also allows querying of network information for specific IP addresses.

### Features
- **System Information Retrieval**:
  - Collects detailed local system information, including OS, processor, memory, disk partitions, and more.
  - Displays the data in a user-friendly format.

- **Network Information**:
  - Retrieves hostname and alias details for specified IP addresses.

- **Data Export**:
  - Saves the gathered system information as a JSON file for easy sharing and analysis.

- **Cross-Platform**:
  - Compatible with Linux, macOS, and Windows systems.

---

## Prerequisites

Ensure you have the following before running the software:
1. **Python 3.10+**: Installed and configured.
2. **Required Python Packages**:
   - `psutil`: For system resource monitoring and hardware information.

   Install dependencies using:
   ```bash
   pip install psutil

