# 简介

本项目旨在让初学者快速入门Activiti。
 
# 框架版本

* Activiti: **5.21.0**

* Spring: **4.1.5.RELEASE**

 
## Maven方式运行

> mvn clean jetty:run -Poracle

xml配置 beans-activiti.xml中设置
	    <!--    oracle 需要设置下面的配置 shema 设置登录的用户名  -->
		<property name="databaseSchema" value="bpm_activiti" />
		
pom中oracle 的profile设置数据的url 用户名 密码等	

如果要是有其他数据库，需要先修改几个hibernate的实体类的id生成策略sequence变为其他的	

# 演示说明文档

  
