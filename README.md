NodeWk 1.0
======
基于Sails.js MVC开发，实现常用的系统、微信、CMS等功能

PS：如果对Java开发框架感兴趣，可以看这里：https://github.com/Wizzercn/NutzWk

======
基于Sailsjs的Node.js开源企业级开发框架

NodeWk 1.0 运行环境：
*   Node 最新版
*   Redis 最新版
*   MySql 5.x

NodeWk 1.0 特性：
*   集成Email服务(nodemailer)
*   集成定时任务(node-schedule)
*   集成验证码插件(captchapng)
*   集成微信api插件(wechat-oauth/wechat-api)
*   集成日志文件插件(winston)
*   集成图片处理插件(gm)
*   集成日期插件(moment)
*   集成数据库备份插件(mysqldump)
*   集成文件打包插件(jszip)
*   集成Ejs模板引擎
*   后台管理界面采用Pjax+Bootstrap
*   支持国际化字符串
*   支持动作链
*   自定义路由


使用说明：
*   搭建Node.js运行环境
*   安装必备组件yum install ImageMagick-c++.x86_64
*   创建空的数据库,使用nodewk.sql还原数据库
*   修改数据库连接及redis /config/custom/mysql.js /config/custom/redis.js
*   npm i 安装(hiredis报错不影响运行)
*   用户名：superadmin  密码：1


在线演示地址
======

http://www.nodeshop.cn/sysadmin               NodeWk 1.0

