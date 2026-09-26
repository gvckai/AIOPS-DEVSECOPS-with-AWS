# My Own Preparation

## How to find IP address in Ubuntu Box

**Usea:**
- `ip a` It print whole ip address - <LOOPBACK,UP,LOWER_UP>
- `ip roate` it prints small information with IP Address
- `/root` — the root user's home folder
- `/home/<username>` — every other user's home folder (e.g. `/home/ec2-user`)

## User and systen info:
```
whoami -  : It prints current logged in use

id - It prints the current user'd UID, GID and group membership
```
```
uname  -  : It prints system or kernel information
```
```
pwd -  : It prints present working directories 
```
# Wownloading and viewing content
- `wget <url>` It downloads a file from internet and save it locally
- `curl <url>` fetches a URL and prints print the to the screen content 
- It does not save to a file default

```
usermod -g devops ramesh      # sets devops as ramesh's primary group
```
```
usermod -aG sre ramesh        # adds ramesh to sre as a secondary group (-a = append)
```
