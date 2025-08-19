Here’s a quick **Ubuntu command cheat sheet** grouped by categories. 🚀

---

## 🔹 **System Information**

```bash
uname -a        # Kernel info
lsb_release -a  # Ubuntu version
hostname        # Display hostname
uptime          # Show how long the system has been running
whoami          # Current logged-in user
```

---

## 🔹 **File & Directory Management**

```bash
pwd                  # Show current directory
ls                   # List files
ls -la               # List with details and hidden files
cd /path/to/dir      # Change directory
mkdir myfolder       # Create directory
rmdir myfolder       # Remove empty directory
rm -rf myfolder      # Remove directory & contents
cp file1 file2       # Copy file
mv file1 file2       # Move/rename file
touch file.txt       # Create empty file
cat file.txt         # Show file content
nano file.txt        # Edit file with Nano editor
```

---

## 🔹 **User Management**

```bash
adduser username       # Add new user
passwd username        # Change user password
su - username          # Switch user
id username            # Show user ID & groups
groups username        # Show groups of user
who                    # Show logged-in users
```

---

## 🔹 **Package Management (APT)**

```bash
sudo apt update              # Update package list
sudo apt upgrade             # Upgrade installed packages
sudo apt install pkgname     # Install package
sudo apt remove pkgname      # Remove package
sudo apt autoremove          # Remove unused packages
dpkg -l                      # List installed packages
```

---

## 🔹 **Process Management**

```bash
ps aux              # Show all processes
top                 # Real-time process viewer
htop                # Better process viewer (install with apt)
kill -9 PID         # Kill process by PID
pkill processname   # Kill process by name
jobs                # List background jobs
fg %1               # Bring job 1 to foreground
```

---

## 🔹 **Networking**

```bash
ip a                 # Show IP addresses
ifconfig             # Network info (need net-tools package)
ping google.com      # Test connectivity
curl ifconfig.me     # Get public IP
netstat -tulnp       # Show listening ports
ss -tuln             # Show open sockets
scp file user@host:/path  # Copy file via SSH
ssh user@host        # Connect to remote server
```

---

## 🔹 **Disk & Storage**

```bash
df -h               # Disk usage
du -sh folder/      # Folder size
lsblk               # List block devices
mount /dev/sdb1 /mnt   # Mount device
umount /mnt         # Unmount device
```

---

## 🔹 **Permissions**

```bash
chmod 755 file      # Change file permissions
chown user:group file  # Change ownership
ls -l               # Show file permissions
```

---

## 🔹 **Logs & Monitoring**

```bash
dmesg               # Kernel messages
journalctl          # System logs
tail -f /var/log/syslog   # Live logs
```

---

## 🔹 **Archive & Compression**

```bash
tar -cvf archive.tar file1 file2   # Create tar archive
tar -xvf archive.tar               # Extract tar archive
gzip file.txt                      # Compress file
gunzip file.txt.gz                 # Decompress file
```

---
