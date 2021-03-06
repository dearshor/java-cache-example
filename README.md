java-cache-example
==================

Memcached和Redis的简单演示，方便快速入门（福利）


## Memcached

Mac OS X可以用macports安装: 
```shell
sudo port install memcached
```
启动服务：
```shell
memcached
```
进入控制台：
```
telnet localhost 11211
```

通过Java操作Memcached：[http://stackoverflow.com/questions/731738/java-memcached-client](http://stackoverflow.com/questions/731738/java-memcached-client)

### Maven依赖
```xml
<dependency>
    <groupId>net.spy</groupId>
    <artifactId>spymemcached</artifactId>
    <version>2.9.1</version>
</dependency> 
```

## Redis

Mac OS X通过macports安装：
```shell
sudo port install redis
```
安装后进入客户端：
```shell
redis-cli
```

快速入门：[http://redis.io/topics/quickstart](http://redis.io/topics/quickstart)

### Maven依赖
```xml
<dependency>
    <groupId>redis.clients</groupId>
    <artifactId>jedis</artifactId>
    <version>2.1.0</version>
</dependency>
```
