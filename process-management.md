# Process Management

## ps aux
Shows all running processes

## top
Live system monitoring

## htop
Better interactive process viewer

## kill
Stops a process using PID
Example:
kill 1234

## systemctl

Start service:
sudo systemctl start ssh

Stop service:
sudo systemctl stop ssh

Restart:
sudo systemctl restart ssh

Status:
systemctl status ssh

## System Monitoring

df -h → disk usage  
du -sh → folder size  
free -m → memory usage  

## Cron

crontab -e

Example:
* * * * * echo "Hello" >> /home/ubuntu/test.log
