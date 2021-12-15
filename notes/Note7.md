### Managing User Accounts
--------------------------
![img 1](2021-12-08%20(25).png)

+ Run the command **adduser** followed by the username.(to add a user in Ubuntu)
+ Run the command **userdel** followed by the username.(to delete a user in Ubuntu)
  + You need to pass the -r option for the command to delete the user and its home directory.

+ The management of users in all linux system is governed by multiple files.
  
### The /etc/login.defs file
+ It contains directives for use in various shadow password suite commands.


### The /etc/default/useradd file
+ This file stores the system default configuration for creating new users with the useradd utility.


### The /etc/passwd file
+ It stores information about every account in a linux system.
+ Each line in the passwd file represents a user.
![img](2021-12-08%20(26).png)


### The /etc/shadow file
+ It contains information about users' password.
![img](2021-12-08%20(27).png)

![img](2021-12-08%20(28).png)

![IMG](2021-12-08%20(29).png)

![IMG](2021-12-08%20(30).png)

![IMG](2021-12-08%20(31).png)

![img](2021-12-08%20(32).png)

![img](2021-12-08%20(33).png)

![img](2021-12-08%20(34).png)

![img](2021-12-08%20(35).png)

### Managing Groups
-------------------
![img](2021-12-08%20(36).png)

### Setting Up the Environment
------------------------------
![img](2021-12-08%20(37).png)

![img](2021-12-08%20(38).png)

![img](2021-12-08%20(39).png)

#### Bash Aliass
----------------
![img](2021-12-08%20(40).png)

Quering users
-------------
![img](2021-12-08%20(41).png)S