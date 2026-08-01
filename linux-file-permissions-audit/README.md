# Linux File Permissions Audit

## Scenario
As a security professional supporting a research team at a large organization, 
I was tasked with ensuring users had appropriate, authorized permissions on 
the file system. This involved examining existing file permissions, comparing 
them against required authorization levels, and correcting any mismatches — 
removing unauthorized access and granting appropriate access where needed.

## Task
Investigated file system permissions for the research team, identified 
discrepancies between current permissions and required authorization, and 
used Linux commands to modify permissions accordingly.

## Approach
- Used `ls -l` to examine existing file and directory permissions
- Identified users/groups with incorrect or excessive access levels
- Applied `chmod` to correct permission levels (read, write, execute) for 
  the appropriate user, group, and other categories
- Used `chown`/`chgrp` where ownership or group assignment needed correction
- Verified changes matched the required authorization model after modification

## Key Skills Demonstrated
- Linux file permission management (`chmod`, `chown`, `chgrp`)
- Access control and authorization auditing
- Attention to least-privilege principles
- Command-line proficiency in Linux security administration
