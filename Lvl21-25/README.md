# Bandit Challenge Levels 21 to 25
## Level 21:
**Thought Process:** Echo the answer using netcat and -l -p to both setup a listener and specify the port where to listen to. Then we run subconnect with the port specified to recive the password for the next level.
---
## Level 22:
**Thought Process:** When we look at the cron job for bandit22 we see that there is an shell script that is being executed every second. We cat the shell and then cat the file to get the password for next level.
---
## Level 23:
**Thought Process:** We follow the same line of commands as we did in the previous level. The sentence “I am user bandit23” is passed to the md5sum command which will calculate the md5sum of the given string and will be stored in mytarget. Then we cat the final step.
---
## Level 24:
**Thought Process:** Create a shell script to contain the password and giveit permissions. Finally we copy the script in the bandit24 folder from where the cron job should execute our file.
---
## Level 25:
**Thought Process:** We create a brute force file to go through all the 10000 files. The sort and grep commands are used to show the result instead of all the failed attempts.
---
