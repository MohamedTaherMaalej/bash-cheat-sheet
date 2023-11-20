# System Information Cheat Sheet

## Table of Contents

- [Basic System Information](#basic-system-information)
- [Hardware Information](#hardware-information)
- [Memory Information](#memory-information)
- [Disk Space Information](#disk-space-information)
- [Network Information](#network-information)
- [Process Information](#process-information)

## Basic System Information

### Display System Information
```bash
uname -a
```

### Display Linux Distribution
```bash
lsb_release -a
```

### Show Kernel Version
```bash
uname -r
```

## Hardware Information

### Display CPU Information
```bash
lscpu
```

### Show GPU Information
```bash
lspci | grep VGA
```

### Display Motherboard Information
```bash
sudo dmidecode -t baseboard
```

## Memory Information

### Show Total Memory
```bash
free -h
```

### Display RAM Usage by Process
```bash
top
```
- Press `q` to exit.

## Disk Space Information

### Show Disk Usage
```bash
df -h
```

### Display Detailed Disk Information
```bash
lsblk
```

## Network Information

### Display Network Interfaces
```bash
ifconfig -a
```

### Show Open Ports
```bash
netstat -tuln
```

### Display External IP Address
```bash
curl ifconfig.me
```

## Process Information

### Display Running Processes
```bash
ps aux
```

### Show Process Tree
```bash
pstree
```

### Display Detailed Process Information
```bash
top
```
- Press `q` to exit.

Feel free to contribute to this cheat sheet by adding more system information commands or improving existing examples. Follow the [Contributing](../CONTRIBUTING.md) guidelines.
