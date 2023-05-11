# The problem
You're new to Linux and you want to upgrade all its packages to the latest versions?
But alas, you're encountering errors whenever you 
```bash
sudo apt upgrade -y
```

# Solution:
There is no essence to this repo if I don't deliver a solution to this problem
- Firstly, whenever you install or deploy a Linux system for the first time, its best if you download the latest version of packages with context to bug fixes, optimisation and security.
- Run the following line:
```bash
sudo apt update -y && sudo apt upgrade -y && sudo apt autoremove -y
```
 # still facing problems? 
 - Check out this [link.](https://github.com/WhiteHatCyberus/Linux-Solutions/blob/main/package%20update%20error%20-%20403%20forbidden.md)
