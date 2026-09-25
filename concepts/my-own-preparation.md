# My Own Preparation

## How to find IP address in Ubuntu Box

**Usea:**
- `ip a` It print whole ip address - <LOOPBACK,UP,LOWER_UP>
- `ip roate` it prints small information with IP Address
- `/root` — the root user's home folder
- `/home/<username>` — every other user's home folder (e.g. `/home/ec2-user`)

Assigning groups:
```
usermod -g devops ramesh      # sets devops as ramesh's primary group
```
```
usermod -aG sre ramesh        # adds ramesh to sre as a secondary group (-a = append)
```