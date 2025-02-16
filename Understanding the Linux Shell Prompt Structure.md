### *Structure of the Shell Prompt*

[root@localhost~]# <br>
[armour@localhost~]$ <br>
[username @ hostname current location} root/user <br>

1. **[user@hostname current_directory]**

    - **user**: Indicates the username of the logged-in user.
        - root: The superuser (administrator) with all privileges.
        - Any other name (e.g., jeevan): A non-root user with limited permissions.
    - **hostname**: The name of the machine or system you are logged into.
        - localhost: The default hostname for a local machine, which can be customized.
    - **current_directory**: Shows the current working directory.
        - ~: Represents the user's home directory (/root for root or /home/username for regular users).
        - If you're in another directory, the prompt displays the actual path, e.g., /etc or /var/log.

2. *Symbol at the End*:

    - **$**: Indicates a non-root user session.
    - **#**: Indicates a root user session.

---

### *Examples of Prompts*

1. **[root@localhost ~]#**

    - **root**: You are logged in as the root (administrator).
    - **localhost**: Hostname of the machine.
    - **~**: Current working directory is the root's home directory (/root).
    - **#**: Superuser privileges.

2. **[jeevan@localhost ~]$**

    - **jeevan**: You are logged in as a regular user named jeevan.
    - **localhost**: Hostname of the machine.
    - **~**: Current working directory is the user's home directory (/home/jeevan).
    - **$**: Limited permissions as a regular user.

---

### *Key Differences Between Root and Non-Root Prompts*

| *Aspect*         | *Root User*              | *Non-Root User*        |
| ------------------ | -------------------------- | ------------------------ |
| *User*           | root                     | Username (e.g., jeevan) |
| *Privileges*     | Full administrative access | Restricted permissions   |
| *Symbol*         | #                        | $                      |
| *Home Directory* | /root                    | /home/<username>       |
