# Problem:

sudo: unable to resolve host <hostname>

# Reason:
  
This may be the result of a recent change in hostname on your linux subsystem
Your new hostname isnt added in the 'hosts' file
  
# Solution?
```bash
cd /etc
```
- Navigate to the 'hosts' file.
- Using sudo, open your hosts file in write mode and add the following sentence

```bash 
  127.0.0.1 <new_hostname>
  ```

# DONE??
- save and close the editor and try sudo
- Run
  ```bash
  sudo apt update -y && sudo apt upgrade -y && sudo apt autoremove -y
  ```
# Concluding remarks
  Woah!! The error is gone! So am I ? Until Next time! Bye!
