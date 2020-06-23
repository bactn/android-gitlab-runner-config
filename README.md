#install jdk environment on Amazon linux 2

yum update

yum install java-1.8.0-openjdk-devel.x86_64

export JAVA_HOME="/usr/lib/jvm/java-1.8.0-openjdk"

echo $JAVA_HOME

export PATH=$PATH:$JAVA_HOME/bin

#install packages

yum install wget tar unzip lib32stdc++6 lib32z1
