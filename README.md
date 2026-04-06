# 🚀 Windows Server Full Admin Automation Script

A PowerShell-based automation solution to quickly deploy a secure and monitored Windows Server environment.

---

## 📌 Features

- ✅ Automated Windows Server Backup (Scheduled)
- ✅ User & Group Management
- ✅ Firewall Hardening (SMB block, RDP restriction)
- ✅ Basic Monitoring (CPU, Event Logs)
- ✅ Security Policy (WDAC / AppLocker ready)
- ✅ Audit Logging Enabled
- ✅ Ready for SIEM Integration

---

## 🧰 Technologies Used

- PowerShell
- Windows Server Backup
- Task Scheduler
- Windows Firewall
- Audit Policy

---

## ⚙️ Setup Instructions

1. Run PowerShell as Administrator
2. Update backup drive:
   ```powershell
   $backupDrive = "E:"
