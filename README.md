#### 介绍:

​    基于springboot开发的网盘存储项目，设想制作成私下朋友圈共享资源的网盘项目，目前仅作展示，可以使用账号和密码123456进行测试

#### 项目主要功能:

​    用户邮箱注册、验证及用户登录；        
​    资源的管理上传、下载、重命名、删除等操作；     
​    邀请其他用户进入朋友圈共享资源；    
​    朋友圈创始人可以对朋友圈资源、文件夹用户进行管理；        
​    实体映射关系:用户与朋友圈多对多，朋友圈与文件夹一对多，文件夹与资源一对多，用户与上传的资源一对多；    
​    每个群提供初始的1G(1024MB)容量，群主群员可以在群中自由分享资源，后续可以通过提升群等级提高群容量；   
​    

#### 使用技术:

​    后端:
​        SpringBoot + MyBatis
​        EnCache缓存 + druid连接池
​        Thymeleaf模板缓存
​        FTP服务器
​    前端:
​        HTML、CSS、JavaScript、JQuery、Ajax等
​        layui、BootStrap等框架
​    部署:
​        阿里云轻量应用服务器
​        Docker 发布
​        FTP 服务
​        MySQL 数据库
​        

####  后续更新计划:

​     加入RabbitMq实现群内聊天、增加QQ登录等其他登录方式、实现支付宝消费更改用户等级和朋友圈等级、增加展示资源的功能、增加二维码分享功能、美化前端页面
