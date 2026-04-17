# Networking Fundamentals

## IP Address

An IP address identifies a device on a network.

Example:
192.168.1.10

Commands:
ip addr
hostname -I

---

## DNS (Domain Name System)

DNS converts domain names into IP addresses.

Example:
google.com → 142.250.x.x

Commands:
nslookup google.com
dig google.com

---

## /etc/hosts

Local file to map domain names manually.

Example:
127.0.0.1 mylocal.dev

---

## SSH (Secure Shell)

Used to securely connect to remote machines.

Generate key:
ssh-keygen -t ed25519

Public key:
~/.ssh/id_ed25519.pub

Private key:
~/.ssh/id_ed25519

---

## SSH Authentication

Instead of passwords, SSH uses keys.

Steps:
1. Generate key
2. Add public key to server/GitHub
3. Connect using SSH

Test:
ssh -T git@github.com

---

## SSH Config

File:
~/.ssh/config

Example:
Host github.com
  HostName github.com
  User git
  IdentityFile ~/.ssh/id_ed25519

---

## Key Takeaways

- IP identifies devices
- DNS converts names to IPs
- /etc/hosts overrides DNS locally
- SSH provides secure access
