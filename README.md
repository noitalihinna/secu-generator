# secu-generator

<br/>

**项目简介** 

项目代码生成器

<br/>

**项目结构** 
```
├─secu-generator  代码生成器
|       └─resources 
|          ├─mapper   MyBatis文件
|          ├─template 代码生成器模板（可增加或修改相应模板）
|          ├─application.yml    全局配置文件
|          └─generator.properties   代码生成器，配置文件

<br/>

**运行环境** 

- JDK1.8
- Maven3.0+

<br/>

**本地运行**

- 通过git下载源码
- 修改application.yml文件，配置数据库账号和密码
- 在secu-generator目录下，执行mvn clean install
