# Linux User Management

## Overview
User management is a core Linux administration task. It involves creating, modifying, and deleting user accounts, as well as managing group membership and account permissions.

## Best Practice
Use groups to assign shared permissions instead of granting access user by user whenever possible.

## Common Commands

### Create a new user
```bash
sudo useradd -m username
Set a password
bash
sudo passwd username
View user identity information
bash
id username
Modify group membership
bash
sudo usermod -aG groupname username
Delete a user
bash
sudo userdel username
Notes
The -m option creates a home directory.
Group membership is useful for permission management.
The id command helps confirm user and group assignments.
Summary
Proper user management helps maintain a secure and organized Linux environment.