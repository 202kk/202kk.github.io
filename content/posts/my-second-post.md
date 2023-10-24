---
title : My Second Post
date : 2023-10-24T22:04:56+09:00
draft : true
---



```
sudo apt-get update
sudo apt install -y git default-jdk flex bison libboost-all-dev libssl-dev maven thrift-compiler vim
git clone https://github.com/apache/iotdb.git
cd iotdb
git checkout v1.2.1
mvn clean package -pl distribution -am -DskipTests -Dthrift.download-url=http://apache.org/licenses/LICENSE-2.0.txt -Dthrift.exec.absolute.path=/usr/bin/thrift
```

```
sudo apt-get update
```

```
sudo apt install -y git default-jdk flex bison libboost-all-dev libssl-dev maven thrift-compiler vim
```

```
git clone https://github.com/apache/iotdb.git
cd iotdb
git checkout v1.2.1
```

```
mvn clean package -pl distribution -am -DskipTests -Dthrift.download-url=http://apache.org/licenses/LICENSE-2.0.txt -Dthrift.exec.absolute.path=/usr/bin/thrift
```
