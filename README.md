# no-oracle-plsql
不安装oracle使用plsql
***
步骤 ：
1. 将这个文件夹配置到系统环境变量path里面
2. 再对系统变量进行增加就可以了
* NLS_LANG = SIMPLIFIED CHINESE_CHINA.ZHS16GBK(或AMERICAN_AMERICA.ZHS16GBK)
* TNS_ADMIN = d:\no-oracle-plsql
* LD_LIBRARY_PATH = d:\no-oracle-plsql
* SQLPATH = d:\no-oracle-plsql
3. 记得将tnsnames.ora这个文件也拷贝到这个文件夹下
***
连接方式
> sqlplus 用户名/密码@ip:端口/数据库服务名
> sqlplus username/password@tnsname
