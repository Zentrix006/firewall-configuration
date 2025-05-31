# 🔥 Firewall Task Report

## 🎯 Objective
Configure firewall rules using UFW to block port 23 (Telnet) and allow port 22 (SSH). Test effectiveness and document the results.

---

## 🛠️ Commands Used
```bash
# Enable UFW
sudo ufw enable

# Check existing rules
sudo ufw status verbose

# Block Telnet (port 23)
sudo ufw deny 23

# Allow SSH (port 22)
sudo ufw allow 22

# Reload UFW
sudo ufw reload

# Verify rules
sudo ufw status numbered

# Remove test rules (if needed)
sudo ufw delete deny 23
sudo ufw delete allow 22
