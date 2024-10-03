# Lab2 info

---
**Command Line Lab** 
### I'm still deciding if I will be using a VM or going through Powershell/Windows terminal (but it's annoying)

---
This lab was running different linux commands
- I have used many of these commands when I was working over the summer
- env, cd, ls, hostname, cat, ifconfig, ping, and netstat I used all of the time.

1. **Hostname**
    * used when grabbing the hostname of the device, in this case it was "raspberry"
    * ![hostName](hostTER.png)

2. **env**
    * This shows the environment variables that the device is using, so in my case it will show a bunch because I am running a VM
    * ![environment](envTER.png)
3. **cd**
    * change directory, so this is used to go into different folders like the "iot" or "dsd" folders that were cloned from the git
4. **ls**
    * this is to list the files inside of a folder/directory
5. **cat**
    * This will print the contents of the file whose name succeeds the phrase cat
6. **ifconfig**
    * this will show the different ips and networks that are curently working on the device
    * ![ifconfig](ifconfigTER.png)
7. **ping**
    * this will ping a secific host and see if messages will send through. You can ping for a specific amount of time or just Ctrl+C to stop and then it will tell if the packages went through or any errors
    *![ping](pingstats.png)
8. **netstat**
    * this will show the network status, so sll of the networks for connections and such with the current device, normally there are a bunch running
    * ![net](netStat.png)
---
## Commands that I haven't used often

1. **df**
    * shows disk space on the file 
    * ![df](df.png)
2. **mkdir**
    * I haven't used this often but it is a commonly used command to make a directory
3. **nano**
    * opens a new text file. You can name it or use nano then name and save
4. **cp [originalfile] [newFile]**
    * copies a file 
5. **mv**
6. **rm**
7. **clear**
8. **man**
9. **uname**

---
I'm running using raspberry pi OS on VM since I wanted to emulate on my machine