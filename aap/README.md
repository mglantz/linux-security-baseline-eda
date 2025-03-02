# Installation
- Create AAP Controller project pointing to this repository
- Create EDA project pointing to this repository
- Create job template called 'Apply Linux security baseline' pointing to the sec-baseline.yml playbook in this repo.
- Create a new Decision Environment for EDA, pointing to quay.io/ansible/ansible-rulebook:latest
- Create a rulebook activation which has AAP Platform credentials added to it and which uses the new Decision Environment you created for EDA
- Activate rulebook activation and see it go..

