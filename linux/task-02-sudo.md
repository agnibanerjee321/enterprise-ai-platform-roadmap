# Task 2.4 — sudo and Privilege Escalation

## Goal

Understand how Linux users temporarily perform administrative actions using sudo.

## Commands Practiced

```bash
groups
whoami
sudo whoami
cat /etc/shadow
sudo head /etc/shadow
sudo journalctl -n 20
sudo chown root:root sudo-practice.conf
sudo sh -c 'echo "sudo_append=true" >> sudo-practice.conf'