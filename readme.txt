本工程为搭建好的IDEA阅读tomcat源码环境

启动类为：org.apache.catalina.startup.Bootstrap

需要设置JVM启动参数为：

-Dcatalina.home=catalina-home
-Dcatalina.base=catalina-home
-Djava.endorsed.dirs=catalina-home/endorsed
-Djava.io.tmpdir=catalina-home/temp
-Djava.util.logging.manager=org.apache.juli.ClassLoaderLogManager
-Djava.util.logging.config.file=catalina-home/conf/logging.properties
