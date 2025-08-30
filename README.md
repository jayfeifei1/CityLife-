CityLife 本地生活平台 是一个基于 Spring Boot + Vue.js 的前后端分离项目。
主要功能围绕用户本地生活需求，包括 商户点评、优惠券秒杀、签到打卡、用户关注、探店笔记 等模块。
本项目适合作为 学习 Spring Boot、Redis、分布式应用开发 的实践项目。
技术栈
Spring Boot
Spring MVC
MyBatis-Plus
Spring Security + JWT
Redis（缓存、分布式锁、消息队列）
MySQL
快速启动
1. 克隆项目
git clone https://github.com/yourname/CityLife.git
cd CityLife

2. 启动后端

配置 MySQL 数据库，导入 sql 文件夹中的初始化脚本

修改 application.yml 数据库和 Redis 配置

启动 Spring Boot 主程序

mvn spring-boot:run
