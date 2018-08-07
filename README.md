# MybatisGenerator
以Maven插件的方式构建的MyBatis逆向工程。
在resources文件夹下应该有数据库配置文件generator.properties
```properties
jdbc.driverLocation=mysql驱动文件的绝对路径
jdbc.driverClass=com.mysql.jdbc.Driver
jdbc.connectionURL=jdbc:mysql://[host]:3306/mybatis?useUnicode=true&characterEncoding=utf-8&useSSL=true
jdbc.userId=
jdbc.password=
