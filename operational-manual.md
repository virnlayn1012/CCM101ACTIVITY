# CLOUDNOVA OPERATIONAL MANUAL

## 1. System Overview
CloudNova is a cloud infrastructure project using
Ubuntu Server, Docker, Docker Compose, WordPress,
and MySQL.

## 2. System Requirements
- VirtualBox
- Ubuntu Server
- Docker
- Docker Compose
- Internet connection

## 3. Accessing the Server
SSH Access:
ssh -p 2222 cloudadmin@127.0.0.1

WordPress Access:
http://localhost:8080

## 4. Managing Docker Containers

Check running containers:
docker ps

Start services:
cd ~/cloudnova
docker compose up -d

Stop services:
docker compose down

## 5. Database Backup

Run manual backup:
~/cloudnova/scripts/backup.sh

Check backup files:
ls -lh ~/cloudnova/backups/

## 6. Automated Backup

View scheduled tasks:
crontab -l

The database backup is scheduled daily
at 2:00 AM.

## 7. Firewall Configuration

Check firewall status:
sudo ufw status verbose

The firewall is configured to deny
incoming connections by default and
allow required SSH and HTTP traffic.

## 8. Troubleshooting

Check Docker containers:
docker ps

Check Docker service:
sudo systemctl status docker

Check cron service:
sudo systemctl status cron

Check backup log:
cat ~/cloudnova/backup.log

## 9. Maintenance

Regularly check container status,
verify database backups, and review
firewall configuration.
