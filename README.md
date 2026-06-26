# Automated-Port-Scanner-Python-Scripting-Network-Automation

## Project Overview

This project is a Python-based multi-threaded port scanner designed to identify open TCP ports on a target host. The scanner utilizes concurrent execution to improve scanning speed and performs service detection and banner grabbing on discovered ports.

The application allows users to specify a target host and a custom port range. Open ports, associated services, and available banners are displayed in a formatted output table.

---

## Features

* Multi-threaded port scanning
* Fast concurrent execution using ThreadPoolExecutor
* TCP service identification
* Banner grabbing capability
* Custom port range selection
* Real-time scan progress tracking
* Colorized terminal output
* Hostname to IP resolution

---

## Technologies Used

* Python 3
* Socket Programming
* Concurrent Futures
* ThreadPoolExecutor
* TCP Networking

---

## Project Workflow

1. User enters target IP address or hostname.
2. User specifies start and end ports.
3. Hostname is resolved into an IP address.
4. Multiple worker threads scan ports concurrently.
5. Open ports are identified.
6. Service names are retrieved.
7. Banner information is collected when available.
8. Results are displayed in a structured format.

---

## Installation

Clone the repository:

git clone https://github.com/yourusername/MultiThreaded-Port-Scanner.git

Navigate into the project directory:

cd MultiThreaded-Port-Scanner

Run the application:

python port_scanner.py

---

## Usage

Example:

Enter your target ip: scanme.nmap.org

Enter the start port: 1

Enter end port: 1000

The scanner will display detected open ports and service information.

---

## Sample Output

Port Scan Results:

Port Service Status

22 ssh Open

80 http Open

443 https Open

---

## Future Enhancements

* UDP port scanning
* Export scan results to CSV
* Save reports to JSON
* Command-line arguments support
* GUI version using Tkinter
* Service version detection
* Network range scanning

---

## Learning Outcomes

This project helped strengthen knowledge of:

* Socket Programming
* Networking Fundamentals
* TCP Communication
* Multithreading
* Concurrent Programming
* Python Error Handling
* Service Enumeration
