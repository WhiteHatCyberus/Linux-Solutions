# Hey again, Do you face the following error?
-----
sudo: unable to resolve host <hostname>
-----
This may be the result of a recent chamge in hostname on your linux subsystem
Your new hostname isnt added in the 'hosts' file
<br>
# Solution???
Its a lengthy process.........no, I'm just playing
All you have to do is 
-----
cd /etc
-----
Youll find a 'hosts' file.
Using sudo, open your hosts file in write mode and add the following sentence
-> 
127.0.0.1 <new_hostname>
for eg: if my hostname is newhost
ADD the following to the hosts file
127.0.0.1 newhost
-----
# DONE??
close the editor and try sudo
Woah!! The error is gone! So am I ?
UNtil Next time! Bye!
-----
