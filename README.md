# Java_Installation
Java installation steps and mapping between different JAVA versions

Follow the link

https://tecadmin.net/install-java-8-on-centos-rhel-and-fedora/

If you have java7 and need to use java8 or map to it, use the following

alternatives --config java


## Setting PATH

edit the ~/.bashrc and add this to end of the file.

PATH=/usr/lib/jvm/java-1.8.0/bin:$PATH

JAVA_HOME=/usr/lib/jvm/java-1.8.0

export PATH

export JAVA_HOME


## If you need to set the multile path for different tool use the following format. ':' is used to seperate between them
PATH=/usr/lib/jvm/java-1.8.0/bin:/root/maven/bin:$PATH

JAVA_HOME=/usr/lib/jvm/java-1.8.0

M2_HOME=/root/maven

export PATH

export JAVA_HOME

export M2_HOME


