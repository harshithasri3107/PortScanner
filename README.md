# Java Port Scanner

A multithreaded TCP port scanner written in Java for educational purposes and authorized security testing.

---

## Overview

This project demonstrates how TCP port scanning works using Java sockets and concurrent threading. The scanner attempts to establish TCP connections to target ports and reports which ports are open and accepting connections.

Port scanning is commonly used in:
- Network administration
- Service discovery
- Security auditing
- Vulnerability assessment
- Cybersecurity reconnaissance

This scanner uses Java networking utilities and thread pooling to efficiently scan multiple ports simultaneously.

---

## Features

- Multithreaded TCP port scanning
- Concurrent scanning using `ExecutorService`
- Fast scanning with thread pooling
- Detects open TCP ports
- Configurable socket timeout
- Lightweight and beginner-friendly
- Uses Java sockets for TCP connections
- Automatic socket resource management
- Demonstrates Java concurrency and networking

---

## How It Works

The scanner:
1. Takes a target host or IP address
2. Iterates through a range of ports
3. Attempts TCP connections to each port
4. Reports ports that successfully accept connections

---

## Testing

This project was tested using the public demo target:

```text
scanme.nmap.org
```

---

## Output

```text
OPEN scanme.nmap.org:22
```

