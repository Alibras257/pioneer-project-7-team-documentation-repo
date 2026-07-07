# Linux Package Management

## Overview
Package management allows Linux administrators to install, update, remove, and manage software packages efficiently.

## Common Package Managers
- `apt` for Debian/Ubuntu systems
- `dnf` for Fedora, RHEL, and Amazon Linux
- `yum` on older RHEL-based systems

## Common Commands

### Update package lists
Ubuntu/Debian:
```bash
sudo apt update
Upgrade installed packages
Ubuntu/Debian:

bash
sudo apt upgrade -y
Install a package
Ubuntu/Debian:

bash
sudo apt install -y nginx
Amazon Linux / RHEL:

bash
sudo dnf install -y nginx
Remove a package
Ubuntu/Debian:

bash
sudo apt remove nginx
Summary
Package managers simplify software installation and maintenance across Linux systems.