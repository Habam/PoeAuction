# PoeAuction
An auction of PoE

## install openjdk
```
sudo yum install java-1.8.0-openjdk-devel
```
#### change default java version
  sudo alternatives --config java
  sudo alternatives --config javac
#### test
  echo ${JAVA_HOME}
  java -version

## install APACHE ANT
http://ant.apache.org/manual/install.html
#### download ANT
  wget http://ftp.tc.edu.tw/pub/Apache//ant/binaries/apache-ant-1.9.6-bin.tar.gz
  tar -zxvf apache-ant-1.9.6-bin.tar.gz
#### set env variable
  sudo vim /etc/profile.d/myenvvars.sh
  export ANT_HOME=/home/ec2-user/poe_auction/bin/apache-ant-1.9.6
  export PATH=$PATH:$ANT_HOME/bin
#### test
  echo ${ANT_HOME}

