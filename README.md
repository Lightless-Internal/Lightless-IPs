# Lightless IPs
Adding these to your system configuration overwrites DNS and makes you connect to the servers directly, bypassing Cloudflare

---
### Windows Format
Add to `C:\Windows\System32\drivers\etc\hosts`. You may need to start `nodepad.exe` as Administrator and load the file from there. There's plenty of tutorials about how to edit this file.
```
sync.lightless-sync.org             95.217.140.233
repo.lightless-sync.org             51.83.43.201
git.lightless-sync.org              51.83.43.201

files1-uk.lightless-sync.org        57.128.169.31
files2-uk.lightless-sync.org        51.195.136.227
files3-uk.lightless-sync.org        51.38.69.13
files4-uk.lightless-sync.org        54.37.17.136

files1-fr.lightless-sync.org        79.137.78.204
files2-fr.lightless-sync.org        79.137.78.205
files3-fr.lightless-sync.org        79.137.78.209
files4-fr.lightless-sync.org        79.137.78.211

files1-us-west.lightless-sync.org   15.204.10.195
files2-us-west.lightless-sync.org   51.81.209.254
files3-us-west.lightless-sync.org   15.204.87.193
files4-us-west.lightless-sync.org   51.81.220.190

files1-us-east.lightless-sync.org   15.204.232.23
files2-us-east.lightless-sync.org   15.204.232.242
files3-us-east.lightless-sync.org   15.204.237.12
files4-us-east.lightless-sync.org   15.204.233.20
files5-us-east.lightless-sync.org   15.204.238.108
files6-us-east.lightless-sync.org   15.204.239.14
files7-us-east.lightless-sync.org   15.204.239.158
files8-us-east.lightless-sync.org   15.204.238.238
```
---
### Linux Format
`sudo nano /etc/hosts`
```
95.217.140.233  sync.lightless-sync.orG
51.83.43.201    repo.lightless-sync.org
51.83.43.201    git.lightless-sync.org

57.128.169.31   files1-uk.lightless-sync.org
51.195.136.227  files2-uk.lightless-sync.org
51.38.69.13     files3-uk.lightless-sync.org
54.37.17.136    files4-uk.lightless-sync.org

79.137.78.204   files1-fr.lightless-sync.org
79.137.78.205   files2-fr.lightless-sync.org
79.137.78.209   files3-fr.lightless-sync.org
79.137.78.211   files4-fr.lightless-sync.org

15.204.10.195   files1-us-west.lightless-sync.org
51.81.209.254   files2-us-west.lightless-sync.org
15.204.87.193   files3-us-west.lightless-sync.org
51.81.220.190   files4-us-west.lightless-sync.org

15.204.232.23   files1-us-east.lightless-sync.org
15.204.232.242  files2-us-east.lightless-sync.org
15.204.237.12   files3-us-east.lightless-sync.org
15.204.233.20   files4-us-east.lightless-sync.org
15.204.238.108  files5-us-east.lightless-sync.org
15.204.239.14   files6-us-east.lightless-sync.org
15.204.239.158  files7-us-east.lightless-sync.org
15.204.238.238  files8-us-east.lightless-sync.org
```