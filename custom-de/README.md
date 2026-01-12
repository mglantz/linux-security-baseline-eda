# Howto build your ServiceNow Decision Environment

1. Install ansible-builder and navigator.
```
dnf install ansible-builder ansible-navigator
```
2. Clone this repository.
3. cd into this directory.
4. Run:
```
ansible-navigator builder build -f execution-environment.yml -t FQDN-for-private-automationhub/de-snow-rhel9
```
5. Push container to Private Automation Hub.
```
podman login FQDN-for-private-automationhub
podman push FQDN-for-private-automationhub/de-snow-rhel9
```
