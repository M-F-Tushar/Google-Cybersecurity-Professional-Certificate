# 🔄 Adding and Deleting Users in Linux 🐧

## Introduction
Welcome back! In this note, we are going to discuss adding and deleting users. This is related to the concept of authentication. 🛡️

## Why Add and Delete Users? 🤔
Authentication is the process of a user proving they are who they say they are in the system. Just like in a physical building, not all users should have access to the system. We need to ensure everyone who should have access, has it, and those who shouldn't, don't. 📋

New users can be new to the organization or new to a group. This could be due to organizational changes or management directives. Similarly, when users leave the organization, they need to be deleted to prevent unauthorized access. 🔐

## Root User and Superuser 🌟
The root user, or superuser, has elevated privileges to modify the system. Regular users have limitations, but root users can perform tasks like creating, modifying, or deleting any file and running any program. Only root users or accounts with root privileges can add new users. 🚀

## Risks of Running Commands as Root ⚠️
Running commands as a root user can be problematic due to:
1. **Security Risks**: Malicious actors target the root account. 🔒
2. **Irreversible Mistakes**: Simple typos can lead to irreversible changes, like deleting important directories. 🛠️
3. **Accountability**: In a multi-user environment, it's hard to track who ran a command if everyone uses the root account. 🕵️‍♂️

## Introducing `sudo` 🧩
`sudo` temporarily grants elevated permissions to specific users, providing a controlled approach compared to root. `sudo` stands for "super-user-do" and lets you execute commands as an elevated user without switching accounts. Running `sudo` prompts you to enter your password. Not all users can use `sudo`—they must be granted access through the `sudoers` file. 🔑

## Adding Users with `useradd` ➕
### Example: Adding a New Sales Representative
To add a new user, use the `useradd` command. We'll add a new representative with the username `salesrep7`:
```bash
sudo useradd salesrep7
This command doesn't display anything on the screen, but if it worked, you'll see a new Bash cursor without an error message. If there was an error, it might be due to a typo or lack of sudo privileges. 🎉

Deleting Users with userdel ➖
Example: Deleting a User
To delete a user, use the userdel command. Imagine the sales representative salesrep7 leaves the company:

bash
sudo userdel salesrep7
Again, a new Bash cursor indicates the command worked successfully. 🚀

Conclusion 🌟
We've covered how to add and delete users and how these actions require sudo. Remember to use these special privileges responsibly to ensure a secure system. Keep practicing, and you'll master these commands in no time! 😊
