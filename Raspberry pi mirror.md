# Raspberry Pi apt package mirror installation
When Raspberry Pi is installed and setup, you may encounter an error while `sudo apt upgrade -y`
> `error: unable to reach ip <[]>`

# Solution
- Navigate to `cd /etc/apt/`
- Open `sources.list` using an editor
- Paste your mirror link.
- Save and Close the editor and run the following commands
```bash
sudo apt update -y && apt upgrade -y && apt autoremove -y
```
> **Note**: Download the latest mirror based on your nearest continent and country [here](https://www.raspbian.org/RaspbianMirrors).
- *Side-Note*: As the time of upload, the nearest mirror in Asia, India is 
```https
https://www.raspbian.org/RaspbianMirrors
```
                
