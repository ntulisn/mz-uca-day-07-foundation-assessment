## Know Your Machine
+ Before changing anything, investigate your Linux server
+ Current User: we use command "whoami": ntulisn
+ Hostname: ntulisn
+ OS: we use cat /etc/os-release: "Ubuntu 26.04.1 LTS"
+ Kernel version: we use uname -r: 6.18.33.2-microsoft-standard-WSL2
+ IP/Network info: ip addr: 172.22.235.194
+ Memory: we use free -h: 7.0Gi
+ Disk space: df -h: 953G Avail
+ Running processes: ps aux
+ Running services: sudo systemctl list-units --type=service --state=running: 16 loaded units listed
+ Listening network ports: ran sudo ss -tulpn: ports listening, tcp:53, tcp:22 & tcp:80

# Engineering question: Why should and eningineer inspect an unfamiliar server before making changes
+ To prevent outages, ensure safety, and avoid breaking dependent systems
