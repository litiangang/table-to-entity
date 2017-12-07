提供两种工具
1、TableTpBean 单纯的生成 bean 带注解注释 
2、mybatis-generator-core-1.3.2 mybatis官方提供的生成工具 
	generatorConfig.xml  配置文件 除了修改表名称 数据库链接地址 账户密码其他不用修改
	mybatis-generator-core-1.3.2.jar 工具包
	mysql-connector-java-5.1.17.jar 数据库连接驱动 如果是oracle 数据库 使用ooracle 驱动
	配置使用 打开cmd 当前目录下输入 java -jar mybatis-generator-core-1.3.2.jar -configfile generatorConfig.xml -overwrite
	文件根据配置包名生成在当前目录下
