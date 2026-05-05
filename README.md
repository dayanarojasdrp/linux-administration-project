# Linux Administration & Troubleshooting Project

## About the Project

This repository documents a practical Linux system administration project focused on configuring, securing, monitoring, and troubleshooting a Linux server environment.

The project covers common operational tasks required in real-world systems, including network configuration, secure remote access, service management, automation, log handling, and system diagnostics.

---

## Skills Demonstrated

* Network configuration using Netplan
* Secure SSH configuration and access control
* Web server setup and management
* File permissions and ownership management
* Service management with systemd
* Backup automation with cron
* Log rotation using logrotate
* Basic intrusion prevention with Fail2ban
* Network diagnostics and testing
* System troubleshooting and problem resolution

---

## Repository Structure

```txt
docs/
  01-netplan.md
  02-secure-ssh.md
  03-web-server.md
  04-var-www-permissions.md
  05-systemd-service.md
  06-cronjob-backup.md
  07-logrotate-config.md
  08-fail2ban.md
  09-network-tests.md
  10-troubleshooting.md

evidence/
  logs/
  outputs/
  screenshots/

README.md
```

---

## Project Modules

### 1. Network Configuration

Configuration and validation of network settings using Netplan and related tools.

### 2. SSH Hardening

Secure configuration of SSH access, including service management and access restrictions.

### 3. Web Server Setup

Installation and configuration of a web server service.

### 4. Permissions and Ownership

Management of file permissions and ownership for service directories.

### 5. systemd Service Management

Creation, control, and troubleshooting of system services.

### 6. Backup Automation

Implementation of automated backups using cron jobs.

### 7. Log Rotation

Configuration and management of log files using logrotate.

### 8. Fail2ban Security

Basic intrusion prevention setup using Fail2ban.

### 9. Network Testing

Diagnostics using tools such as:

* ping
* curl
* ss
* ip
* traceroute

### 10. Troubleshooting

Analysis and resolution of common Linux system issues.

---

## Troubleshooting Scenarios

| Scenario                       | Tools Used                | Result                                      |
| ------------------------------ | ------------------------- | ------------------------------------------- |
| SSH connection issue           | systemctl, journalctl, ss | Service status verified and access restored |
| Web directory permission issue | ls, chmod, chown          | Correct permissions and ownership applied   |
| Network connectivity issue     | ping, ip route, curl      | Connectivity and routing validated          |
| Log growth issue               | logrotate                 | Log rotation configured and stabilized      |

---

## Evidence

This repository includes practical evidence of executed tasks, such as:

* Command outputs
* System logs
* Configuration files
* Screenshots of system behavior

These elements support the reproducibility and validation of the documented work.

---

## Purpose

The purpose of this project is to demonstrate practical Linux system administration skills through documented, reproducible configurations and troubleshooting scenarios.

---

## Usage

The modules can be followed independently or as a complete workflow.

It is recommended to execute the commands in a Linux environment (local machine, virtual machine, or remote server) to fully understand their behavior.

---

## Notes

This project focuses on command-line administration and does not include graphical tools.

---

## Author

Developed by Dayana Rojas

