## FILE PERMISSIONS AND OWNERSHIP
File permissions are represented by a series of characters that indicate the permissions for the owner, the group, and others. The permissions are:

r: Read permission
w: Write permission
x: Execute permission

For example, the permission rwxr-xr-- means the owner can read, write, and execute the file, the group can read and execute, and others can only read.

## Numeric Representation of Permissions
File permissions can also be represented numerically, which is often used in scripts and command-line operations:

0: No permission
1: Execute permission
2: Write permission
3: Write and execute permissions
4: Read permission
5: Read and execute permissions
6: Read and write permissions
7: Read, write, and execute permissions
For example, the numeric permission 755 means the owner can read, write, and execute (7), and the group and others can read and execute (5).

## File Ownership
1. chmod- change file permissions
    The chmod command has several options to customize its behavior:

    -R: Change files and directories recursively.
    -v: Output a diagnostic for every file processed.

2. chown- change file ownership
    The chown command has several options to customize its behavior:

    -R: Change files and directories recursively.
    -v: Output a diagnostic for every file processed.

3. chgrp- change file group
    The chgrp command has several options to customize its behavior:

    -R: Change files and directories recursively.
    -v: Output a diagnostic for every file processed.

## User Authentication
Linux stores user information in two critical files:
    /etc/passwd: contains basic user information, including usernames and UIDs.
    /etc/shadow: stores encrypted passwords and account expiration information.

## Security Tools
UFW(uncomplicated firewalls):
enable firewall: sudo ufw enable
allow traffic: sudo ufw allow 22
