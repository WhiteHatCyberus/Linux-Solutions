# Problem:
```
zsh: corrupt history file /home/hostname/.zsh_history
```
# Reason
This maybe due to unexpected termination while installing, unpacking or reading packages.
# Solution:
```
cd ~
mv .zsh_history .zsh_history_old
strings .zsh_history_old > .zsh_history
fc -R .zsh_history
```
