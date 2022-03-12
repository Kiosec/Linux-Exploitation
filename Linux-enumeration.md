## Internal Enumeration

## ID and location
```
id
pwd
```

## OS / Version / Architecture
```
cat /etc/*-release
uname -i
uname -a
uname -r
cat /proc/version
hostnamectl | grep Kernel
lsb_release -a (Debian based OSs)
```

## Packaged installed
```
dpkg -l (Debian based OSs)
rpm -qa (CentOS / openSUSE )
```

## Running services and network services
```
ps aux
netstat -antup
```

## Network
```
ifconfig
ip addr show
arp -a
```

## Search a file
```
find . -name "*.txt"
```

## Read SSH key
```
ls -la /home /root /etc/ssh /home/*/.ssh/; locate id_rsa; locate id_dsa; find / -name id_rsa 2> /dev/null; find / -name id_dsa 2> /dev/null; find / -name authorized_keys 2> /dev/null; cat /home/*/.ssh/id_rsa; cat /home/*/.ssh/id_dsa

cat ~/.ssh/authorized_keys
cat ~/.ssh/identity.pub
cat ~/.ssh/identity
cat ~/.ssh/id_rsa.pub
cat ~/.ssh/id_rsa
cat ~/.ssh/id_dsa.pub
cat ~/.ssh/id_dsa
cat /etc/ssh/ssh_config
cat /etc/ssh/sshd_config
cat /etc/ssh/ssh_host_dsa_key.pub
cat /etc/ssh/ssh_host_dsa_key
cat /etc/ssh/ssh_host_rsa_key.pub
cat /etc/ssh/ssh_host_rsa_key
cat /etc/ssh/ssh_host_key.pub
cat /etc/ssh/ssh_host_key
```


## Automated enumeration

LinEnum :
<https://github.com/rebootuser/LinEnum>

Linprivchecker.py :
<https://github.com/reider-roque/linpostexp/blob/master/linprivchecker.py>

Unix-privesc-check :
<http://pentestmonkey.net/tools/audit/unix-privesc-check>

Linuxpriveschecker.py :
<https://raw.githubusercontent.com/swarley7/linuxprivchecker/master/linuxprivchecker.py>

LinPeas.exe :
<https://github.com/carlospolop/PEASS-ng/releases/tag/20220220>
