1. karaf, maven environment

build:~$ cd; mkdir Downloads Applications
build:~$ cd Downloads
build:~$ wget http://archive.apache.org/dist/karaf/3.0.3/apache-karaf-3.0.3.tar.gz
build:~$ wget http://archive.apache.org/dist/maven/maven-3/3.3.1/binaries/apache-maven-3.3.1-bin.tar.gz
build:~$ tar -zxvf apache-karaf-3.0.3.tar.gz -C ../Applications/
build:~$ tar -zxvf apache-maven-3.3.1-bin.tar.gz -C ../Applications/ 

2. export ONOS_ROOT=~/onos-1.2.0-build
3. source $ONOS_ROOT/tools/dev/bash_profile 
4. mvn clean install
5. If you want to read more, https://wiki.onosproject.org/display/ONOS/Installing+and+Running+ONOS
