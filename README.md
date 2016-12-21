# (c) copyright 2016 Martin Lurie / sample code / not supported 
 df -h  # check for free space
 #insure host names all resolve the same
 # fully qualified domain name is HIGHLY recommended
 host
 nslookup host
 nslookup ipadd
 ping whatever # make sure you have internet
 getenforce  # make sure SE linux is turned off - note thi requires a reboot
 chkconfig iptables off # or open all the required ports for hadoop
 wget http://archive.cloudera.com/cm5/installer/latest/cloudera-manager-installer.bin
 
