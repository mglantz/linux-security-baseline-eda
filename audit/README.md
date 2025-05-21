# Installation
- On clients you want to protect:
- Install audit, systemctl enable auditd, put the auditd.conf in /etc/audit, put in place audit.rules file in /etc/audit/rules.d/audit.rules and put the syslog.conf into /etc/audit/plugins.d/ and then reboot the machine
