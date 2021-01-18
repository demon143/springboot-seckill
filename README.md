# 互联网开发实践大作业

## 高并发手机秒杀系统

## 开发需要配置安装的环境				

IntelliJ IDEA 2017.3.1 x64

JDK：1.8

Maven：3.2.2

Mysql：5.5

SpringBoot：1.5.9.RELEASE

redis：3.2

RabbitMQ：3.7.14





## 部署说明

1. 下载代码 git clone https://github.com/pitt1997/Seckill 将项目下载到IDEA里面
2. 运行sql文件夹下的sql文件
3. 到src/main/resources下的application.properties下修改你的数据库链接用户名与密码
4. 安装redis、mysql、rabbitmq、maven等环境
5. 启动前，检查配置 application.properties 中相关redis、mysql、rabbitmq地址
6. 在数据库秒杀商品表里面设置合理的秒杀开始时间与结束时间
7. 登录地址：http://localhost:8080/login/to_login
8. 商品秒杀列表地址：http://localhost:8080/goods/to_list

## 其它说明
1.使用技术：前端：Thymeleaf、Bootstrap、JQuery；后端：SpringBoot、Mybatis；中间件：RabbitMQ、Redis、Druid

2.数据库共有一千个用户左右（手机号：15200000000~15200000997 密码为：123456），为压测准备的。（使用 com.ljs.miaosha.util.UserUtil.java该类生成的，生成token做压测的方法也是在此类里面）



# springboot-seckill
