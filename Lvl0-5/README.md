# Bandit Challenge Levels 0 to 5
## Level 0:
**Thought Process:** The challenge provides the hostname, username, and port number. Therefore using SSH to log in with the given credentials is obvious.
---
## Level 1:
**Thought Process:** The file is located in the home directory, and cat is the simplest way to display its contents.
---
## Level 2:
**Thought Process:** A file named '-' can be interpreted as an option. Using ./- specifies the file’s path, allowing cat to read it.
---
## Level 3:
**Thought Process:** A file named 'spaces in this filename' cannot be accessed by cat, thus we enclose it in double quotes, specifying it.
---
## Level 4:
**Thought Process:** The file is hidden and can be viewed by using the ls -a command. Then it can be catted to show the contents.
---
## Level 5:
**Thought Process:** The find command helps identify the type of file, and you can then use cat to read the correct one.
---