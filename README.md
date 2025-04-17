
# Task 7 - Monitor System Resources using Netdata

## 🚀 DevOps Internship Task

This task involved installing and running **Netdata** using Docker locally to monitor real-time system performance.

## 🛠 Tools Used
- Netdata
- Docker

## 📌 Objective
To monitor:
- CPU, memory, disk, and network usage
- System alerts
- Real-time charts

## ⚙️ Steps Followed

1. Ran this Docker command:
   ```bash
   docker run -d --name=netdata -p 19999:19999 --cap-add=SYS_PTRACE --security-opt apparmor=unconfined netdata/netdata

2. Opened browser and accessed:
   http://localhost:19999
3. Captured the Netdata dashboard.
