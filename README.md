# Python Port Scanner

This is a simple Python-based port scanner used to identify open ports on a specified IP address.

## Overview

The script scans ports **1 through 1024** by attempting to establish a connection to each port on the target IP. If a connection is successful, the port is considered **open** and is displayed in real-time.

## How It Works

The program uses two core functions:

- `scan_ports`:  
  Iterates through ports 1 to 1024 and passes each one to `scan_port`.

- `scan_port`:  
  Attempts to connect to a single port on the given IP.  
  - If a connection is made, it’s marked as open.  
  - If not, it’s assumed closed.

## Usage

1. Run the Python script.
2. When prompted, input the IP address you want to scan.
3. The script will print open ports as it finds them.

## Example

```
$ python port_scanner.py
Enter IP to scan: 192.168.1.1
[+] Port 22 is open
[+] Port 80 is open
```

## Disclaimer

This tool is intended for educational and authorized use only. Do not scan systems you do not have permission to test.

---

Made with 💻 by [Rene Ayers]
