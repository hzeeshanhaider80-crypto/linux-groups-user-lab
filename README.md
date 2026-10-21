<<<<<<< HEAD
Linux Users and Groups Management 
 Overview

Today I practiced Linux user and group management, including creating users, managing groups, changing file ownership, and setting permissions.

 Topics Covered
Check current user using whoami
View user and group information using id and groups
View users and groups using /etc/passwd and /etc/group
Create users using useradd
Set passwords using passwd
Create groups using groupadd
Add users to groups using usermod
Remove users from groups using gpasswd
Change file ownership using chown
Change group ownership using chgrp
Manage file permissions using chmod
Delete users and groups using userdel and groupdel
 Commands Practiced
whoami
id
groups
sudo useradd -m ali
sudo passwd ali
sudo groupadd developers
sudo usermod -aG developers ali
groups ali
sudo gpasswd -d ali developers
sudo chown ali file.txt
sudo chgrp developers file.txt
ls -l file.txt
chmod 755 file.txt
sudo userdel ali
sudo groupdel developers

 Important Linux Files
File	Purpose
/etc/passwd	User account information
/etc/shadow	Protected password information
/etc/group	Group information
 Key Learnings
User: An individual account on a Linux system.
Group: A collection of users.
chown: Changes file ownership.
chgrp: Changes group ownership.
chmod: Changes file permissions.
 Goal

Build practical Linux administration skills through daily terminal practice.


=======
# linux-groups-user-lab
this directory contain all about user &amp;groups
>>>>>>> e1bed31b16ab84c0cf48f7835bc96939731ab511
