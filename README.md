# SSH Honeypot Intrusion Detector

A security project to detect, log, and alert on SSH brute-force attempts using:

- `auditd` and `fail2ban` on Kali Linux
- `iptables` for auto-blacklisting
- Structured email alerts with GeoIP and whois info

## 🛠 Technologies Used
- auditd
- iptables
- msmtp
- bash scripting
- GeoIP / whois tools

## 📸 Screenshots
_Add sample log screenshots or email alerts here_

## 📁 Files
- `send-structured-alert.sh`
- `watch-honeypot-log.sh`
- `honeypot-watcher.service`

## 🔐 Security Measures
- MAC filtering
- auto-blacklist
- log persistence

## 📄 License
MIT
