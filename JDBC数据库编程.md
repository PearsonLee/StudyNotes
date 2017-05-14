# 数据库编程

JDBC



odbc，为C语言访问数据库提供了一套编程接口

jdbc，为java提供了。。。。



根据api编写的程序都可以与驱动管理器进行通信，而驱动管理器则通过驱动程序与实际的数据库进行通信



SQL标准语句中，字符串是用*单引号* 括起来的

可以从多个表中选择数据

select * from table_a, table_b



#### 配置JDBC 数据库URL

连接数据库时，需要各种与数据库类型相关的参数，如：主机名，端口号和数据库名

jdbc使用一种与普通url类似的语法来描述数据源。

JDBC URL的一般语法为：

jdbc:subprotocol:other stuff

(subprotocol，连接到数据库的具体驱动程序

other stuff 参数的格式随有使用的subprotocol不同而不同。具体格式，需要查阅数据库供应上提供的相关文档)



#### 对应数据库的驱动程序jar文件

（驱动程序的jar文件中包含META-INF/services/java.sql.Driver文件的jar文件可以自动注册驱动器类）