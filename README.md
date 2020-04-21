# notemark
主要是为了记录日常学习的笔记。

exception项目

exception项目javaweb原生项目。
该次提交主要配置了一些基础结构

1、统一异常控制
2、统一编码控制
3、登录过滤控制

其中碰到的问题有：
1、虽然配置了统一编码过滤，但是对于get请求是没有生效的，需要再tomcat的server中配置编码
2、使用jsp时当用到el表达式时需要引用，但是引用了依旧提示cannot resolve uri...这样的错误，是因为用到el表达式需要导入相应的jar包，可以再pom.xml中详细看到。
3、所配置的文件都在web.xml中能得到索引。
