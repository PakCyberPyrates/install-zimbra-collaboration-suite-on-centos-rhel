Step 1: Install System Packages

yum -y install unzip net-tools sysstat openssh-clients perl-core libaio nmap-ncat libstdc++.so.6

2.

getenforce

setenforce 0

getenforce


3.


systemctl stop postfix

systemctl disable postfix

yum remove postfix
