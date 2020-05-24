# SpringBootCMS
- 做个简单易用的SpringBootCMS
- BackEnd后台:SpringBoot2 + MybatisPlus3 + Freemarker
- AdminUI管理页面:LayMini2(based on LayUI)
- FrontEndUI前端页面:Bootstrap3/4

# Author
- Moshow郑锴@zhengkai.blog.csdn.net

#功能描述
- 用户、角色(普通用户1/管理员9)、菜单管理(二级菜单)功能。
- 表单管理功能，提供动态表单定义与提交功能，可自定义项。
- 活动管理功能，提供活动发布与签到功能。
- 文章管理功能，提供文章列表、目录列表(二级目录)、附件管理功能。

#TODO LIST
- 文章与目录模块
- 权限模块Security/Shiro+
- JWT模块
- FrontEndUI
- EhCache缓存(默认EhCache JAVA缓存，可自行切换为更强大的Redis)
- Password MD5加密

#LOGIN INFO
- http://localhost:8888/cms/
- admin/123456

#UPDATE
|日期|内容|
|----|----|
|2020-05-24|init，初始化项目|