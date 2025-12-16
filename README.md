# Linux-Commands-for-DevOps-Engineers

Essential Linux commands cheat sheet for DevOps Engineers

## 📁 1. File and Directory Management

```bash
ls -l           # List files in long format
cd /path        # Change directory
pwd             # Print current working directory
mkdir newdir    # Create a new directory
rm file         # Remove file
rm -r dir       # Remove directory recursively
cp file1 file2  # Copy file
mv old new      # Move or rename file
find / -name "file.txt"  # Search for a file
```

## 🔐 2. Permissions and Ownership

```bash
chmod 755 script.sh         # Change permissions
chown user:group file       # Change ownership
ls -l                       # Check permissions
```

## 👤 3. User and Group Management

```bash
useradd newuser
passwd newuser
usermod -aG group user
groupadd devops
id user
```

## ⚙️ 4. Process and Service Management

```bash
top
htop
ps aux
kill -9 PID
systemctl status nginx
systemctl start nginx
systemctl stop nginx
```

## 🌐 5. Networking

```bash
ip a
ifconfig
ip route
ping 8.8.8.8
traceroute google.com
netstat -tulnp
ss -tulwn
```

## 💾 6. Disk and File System

```bash
df -h
du -sh *
mount /dev/sdb1 /mnt
umount /mnt
lsblk
```

## 📦 7. Archiving and Compression

```bash
tar -czvf archive.tar.gz dir/
tar -xzvf archive.tar.gz
zip -r file.zip folder/
unzip file.zip
```

## 📥 8. Package Management

```bash
Debian/Ubantu
apt update && apt upgrade
apt install nginx
apt remove nginx
RHEL/CentOS
yum update
```

## ⏰ 9. Crontab (Scheduling Jobs)

```bash
crontab -e
crontab -l
```

## 🔑 10. SSH and Remote Access

```bash
ssh user@ip_address
scp file user@ip:/path
ssh-keygen
ssh-copy-id user@ip
```

## 📊 11. Logs and Monitoring

```bash
tail -f /var/log/syslog
journalctl -xe
uptime
dstat
```

## 🛠 12. System Info and Debugging

```bash
uname -a
hostname
free -h
strace ./script.sh
```

## 💡 Tip

Practice these commands in VirtualBox / VMware, AWS EC2, Azure VM, GCP Compute Engine.

Hands-on practice is the key to mastering DevOps 🚀

Real-world familiarity builds confidence for troubleshooting and automation tasks.
