#zookeeper 服务启动
bin/zookeeper-server-start.sh config/zookeeper.properties

#kafka 服务启动
bin/kafka-server-start.sh config/server.properties &
