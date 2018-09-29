# install ifconfig command for Ubuntu
apt-get install net-tools

ping command for ubuntu:
apt-get install iproute2

# Check the version of current linux version

uname -a
cat /etc/pro
cat /etc/lsb-release

# check where the JDK installed
[ps@localhost shell]$ which java
/usr/bin/java
[ps@localhost shell]$ ls -lrt /usr/bin/java
lrwxrwxrwx. 1 root root 22 Sep 28 10:46 /usr/bin/java -> /etc/alternatives/java
[ps@localhost shell]$ ls -lrt /etc/alternatives/java
lrwxrwxrwx. 1 root root 73 Sep 28 10:46 /etc/alternatives/java -> /usr/lib/jvm/java-1.8.0-openjdk-1.8.0.181-3.b13.el7_5.x86_64/jre/bin/java

# set environment for maven
export MVN_HOME=/usr/local/apache-maven-3.5.4
export PATH=$PATH:$MVN_HOME/bin

