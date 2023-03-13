# problem:
cannot edit a  file or folder? or do you always have to enter sudo password to access or manipulate a file or folder?
# the solution?
- you need to give the particular host its permissions to either read, write or execute a file or a folder, this is done by the `chmod` function.
```bash
sudo chmod -R hostname:host <filename or foldername>
```
