# 自动生成mybatis的mapper、service、controller和entity

- 运行入口：MpGenerator.java

- 配置文件：mybatis-plus.properties

## 重要配置项

- parent：生成的文件路径
- OutputDirXml：生成的xml文件的存储文件夹
- OutputDir：生成的其他文件的存储文件夹
- url：数据库访问路径
- userName：数据库用户名
- password：密码
- 其他配置项无效

具体要生成的表格名称在MpGenerator.java的main函数中进行设置