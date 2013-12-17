from centos

maintainer Dan Drown <dan@drown.org>

run sed -i '/main/a\
proxy=http://10.1.2.137:3128' /etc/yum.conf

run yum -y update

run yum -y install http://mirror.us.leaseweb.net/epel/6/i386/epel-release-6-8.noarch.rpm

run touch /etc/sysconfig/network
