# Installation
- Put rsyslog-server.conf in /etc/rsyslog.conf on the central rsyslog server
- Put rsyslog-client.conf on protected clients, adjusting remote rsyslog server first, then putting it in /etc/rsyslog.conf
- Install audispd-plugins on protected clients:
```
dnf install audispd-plugins
```
