# Problem:
```
Err:1 http://kali.download/kali kali-rolling/main amd64 sbd amd64 1.37-1kali4
403  Forbidden [IP: 10.0.4.12 8090]
```
# Solution:
```
cd /etc/apt
sudo nano sources.list 
```
replace:
```
deb http://http.kali.org/kali kali-rolling main non-free contrib
```
TO:
```
deb https://http.kali.org/kali kali-rolling main non-free contrib
```

# Whats different?
change `http` to `https` and you're good to go!
