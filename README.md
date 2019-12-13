# spring-cloud-eureka-server
基于spring-cloud-config2.0.3构建的服务配置中心。有个很重要的问题请看 Wiki 。

service-url ；这个为高可用时写，将本服务注册到另外两或多个服务上；使用,号隔开。部署了3个服务，就写另外两个地址，