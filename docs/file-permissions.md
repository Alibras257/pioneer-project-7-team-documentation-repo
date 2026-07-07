# Linux File Permissions

## Overview
Linux file permissions control who can read, write, or execute files and directories. Permissions are essential for enforcing security and limiting unauthorized access.

## Best Practice
Avoid using `777` permissions unless absolutely necessary, as it grants full access to everyone.


## Permission Types
Linux permissions are divided into:
- read (`r`)
- write (`w`)
- execute (`x`)

These permissions apply to:
- owner
- group
- others

## Common Commands

### View permissions
```bash
ls -l
Change permissions
bash
chmod 755 filename
Change owner
bash
chown user:group filename
Change group ownership
bash
chgrp groupname filename
Example
bash
chmod 770 shared_directory
This gives:

full access to owner
full access to group
no access to others
Summary
File permissions are fundamental to Linux security and system administration.