### Download and install openfortivpn

```
$ wget -c https://deb.debian.org/debian/pool/main/o/openfortivpn/openfortivpn_1.8.1-1_amd64.deb
$ sudo dpkg -i openfortivpn_1.8.1-1_amd64.deb
```

### Download and install openfortivpn dependencies
```
$ wget -c http://archive.ubuntu.com/ubuntu/pool/main/o/openssl/libssl1.1_1.1.0g-2ubuntu4_amd64.deb
$ sudo dpkg -i libssl1.1_1.1.0g-2ubuntu4_amd64.deb
```

### Edit config file
```
 host = 
 port = 
 username = 
 password = 
 trusted-cert =
```

## Start
```
$ ./run.sh
```






### Extra - Adding shotcut

```
$ gedit ~/.local/share/applications/openfortivpn.desktop
```

### Add to openfortivpn.desktop and save
```
  [Desktop Entry]
  Type=Application
  Terminal=false
  Name=Openfortivpn
  Exec=/path/to/file/run.sh  <--- put your path here
```
