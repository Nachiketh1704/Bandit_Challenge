# Bandit Challenge Levels 6 to 10
## Level 6:
## Level 0:
**Thought Process:** The challenge provides the hostname, username, and port number. Therefore using SSH to log in with the given credentials is obvious.
![Screenshot for Level 0](Bandit0.png)
---
## Level 1:
**Thought Process:** The file is located in the home directory, and cat is the simplest way to display its contents.
![Screenshot for Level 1](Bandit1.png)
---
## Level 2:
**Thought Process:** A file named '-' can be interpreted as an option. Using ./- specifies the file’s path, allowing cat to read it.
![Screenshot for Level 2](Bandit2.png)
---
## Level 3:
**Thought Process:** The password is in a hidden file, which can be revealed using ls -a.
![Screenshot for Level 3](Bandit3.png)
---
## Level 4:
**Thought Process:** The find command helps identify the type of file, and you can then use cat to read the correct one.
![Screenshot for Level 4](Bandit4.png)
---
## Level 5:
**Thought Process:** The find command is very useful for searching files by specific attributes like size.
![Screenshot for Level 5](Bandit5.png)
---