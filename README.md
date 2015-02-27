# MTA-Linux-CentOS-x64--Installer
<br>

Compatibility
----------------
+ CentOS 6/7 64bit

<br/>

one line Install
-----------
#### Run the following one liner as root
```
yum install -y wget;yum install -y unzip;yum install -y libstdc++.i686 unzip zlib.i686 ncurses-libs.i686;yum install -y screen;wget http://linux.mtasa.com/dl/141/multitheftauto_linux-1.4.1.tar.gz;wget http://linux.mtasa.com/dl/141/baseconfig-1.4.1.tar.gz;tar -xf multitheftauto_linux-1.4.1.tar.gz;tar -xf baseconfig-1.4.1.tar.gz;mv baseconfig*/* multitheftauto_linux*/mods/deathmatch;cd multitheftauto_linux-1.4.1;mkdir mods/deathmatch/resources;cd mods/deathmatch/resources;wget http://mirror.mtasa.com/mtasa/resources/mtasa-resources-latest.zip;unzip mtasa-resources-latest.zip;cd ~;
```

-----------
#### Run server
```
cd multitheftauto_linux-1.4.1
./mta-server

```
-----------
#### Run server with screen
```
screen -d -m -S mta-server /root/multitheftauto_linux-1.4.1/mta-server
```
-----------
#### View Server running with screen
```
screen -r /mta-server
```


