# Task 7 - Monitor System Resources using Netdata

## 🚀 DevOps Internship Task

This task involves installing and running **Netdata** using Docker on an EC2 instance to monitor system performance metrics in real time.

## 🛠 Tools Used
- Netdata (monitoring tool)
- Docker
- AWS EC2

## 📌 Objective
To set up Netdata on a remote VM and monitor:
- CPU, memory, disk, and network usage
- Docker container stats
- Alerts and real-time dashboards

## ⚙️ Steps Followed
1. Launched Docker container:
   ```bash
   docker run -d --name=netdata -p 19999:19999 --cap-add=SYS_PTRACE --security-opt apparmor=unconfined netdata/netdata
2. Opened browser and accessed:
   http://<ec2-public-ip>:19999
3. Captured the Netdata dashboard.
