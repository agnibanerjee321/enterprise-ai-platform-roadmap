# Task 2.3 — Linux File Permissions

## Goal

Understand Linux file ownership, permissions, chmod, and permission numbers.

## Commands Practiced

```bash
mkdir -p linux/permission-lab
touch app.conf deploy.sh secret.txt
ls -l
echo "server_port=8080" > app.conf
echo "echo Deploying application" > deploy.sh
echo "password=NeverCommitSecrets" > secret.txt
./deploy.sh
chmod +x deploy.sh
chmod 600 secret.txt
chmod 644 app.conf
ls -ld permission-lab