# 🔍 Python Port Scanner

A multithreaded TCP port scanner built in Python — similar to Nmap's basic functionality.

## Features
- Multithreaded scanning (fast!)
- Automatic service name detection
- Clean CLI with colored output
- Customizable port range and thread count

## Usage
```bash
python scanner.py <host> [-s start_port] [-e end_port] [-t threads]
```

## Example
```bash
python scanner.py scanme.nmap.org -s 1 -e 1024
```

## Concepts Covered
- TCP sockets and the connect handshake
- Threading with `concurrent.futures`
- CLI argument parsing

## ⚠️ Legal Notice
Only scan systems you own or have explicit permission to scan.
