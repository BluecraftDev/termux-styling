# Made By Code with Bluecraft
### This script will make your termux look better. Enjoy! ! 
#### Installing
1. apt update
2. pkg install git 
3. git clone https://github.com/BluecraftDev/termux-styling
4. cd termux-styling 
5. chmod +x *
6. ./setup.sh or sh setup.sh to install styling. 


#### Features
##### Custom Commands
+ shell **[ usage shell \* = sh \*.sh OR bash \*.bash ]**
+ txt **[ usage txt \* = cat \* ]**
+ ins **[ usage ins \* = pkg install \* ]**
+ ains **[ usage ains \* = apt install \* ]**
+ dir **[ usage dir = ls ]**
+ update **[ usage update = apt-get update && apt-get upgrade]**
+ cds **[ usage cds dir_name(_supports pattern matching and sub-directory navigation_) ]**
+ prm **[ usage prm ext = chmod 777 \*.ext ]**
+ md **[ usage md foldername = mkdir foldername]**
+ msf **[ usage msf = msfconsole]** *to launch metasploit*
+ msfdb **[ usage msfdb = initdb $PREFIX/var/lib/postgresql && pg_ctl -D $PREFIX/var/lib/postgresql start]** *to connect to metasploit database if it isn't connected automatically **which is often**.*

###### CDS command guide
+ **Options**
  + **-i** *makes the search case insensitive*

#### Uninstalling
1. Run the script again to uninstall styling.
