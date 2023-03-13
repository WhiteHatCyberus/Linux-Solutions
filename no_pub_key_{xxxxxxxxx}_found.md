# Problems
while doing system modifying operations like 
```
sudo apt-get -y install <application>
apt update & apt upgrade & apt autoremove
```
- Do you face errors like:
``` Err:18 http://dl.google.com/linux/chrome/deb stable Release.gpg
The following signatures couldn't be verified because the public key is not available: NO_PUBKEY {XXXXXXXXXXXXXXXXX} 
```
- These keys are often placed in the installer config or added to facilitate the installation or modification of applications, webpages etc.

# Solution
type the command
```
sudo apt-key adv --keyserver keyserver.ubuntu.com --recv-keys {XXXXXXXXXXXXXXXXXX}
```
# Alternative Solution

if this doesn't resolve the issue , which it normally always works, do check your network connection. 

# Concluding Remarks
Thank you!!! Until next Time - White Hat Cyberus
