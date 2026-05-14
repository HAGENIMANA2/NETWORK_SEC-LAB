# Daily Log Review Procedure

## Author: Jean de Dieu HAGENIMANA - CCNA Certified

---

## Objective
To ensure timely detection of security incidents through systematic log review of network devices, firewalls, and servers.

---

## Review Schedule

| Frequency | Duration | Responsible |
|-----------|----------|-------------|
| Daily | 30 minutes | Network Security Engineer |
| Weekly | 2 hours | Network Security Engineer + Lead |
| Monthly | 4 hours | Full security team |

---

## Step 1: Priority Review (First 15 minutes)

### Firewall Logs

### IDS/IPS Alerts (Critical & High)

### Authentication Logs
```bash
# Linux command examples
grep "Failed password" /var/log/auth.log | tail -20
grep "Invalid user" /var/log/auth.log | tail -20
lastb | head -20  # Failed login attempts
