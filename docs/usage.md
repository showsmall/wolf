
## 添加/管理应用步骤

* 添加应用`application`
* 添加管理员用户`user`
  * 添加新用户, 并设置成管理员. 将新应用授权给该管理员用户.
  * 使用现有用户, 设置成管理员. 将新应用授权给该管理员用户.
* 添加可以访问该应用的普通用户`user`.

* 针对不同的接口, 或业务添加不同的权限`permission`
  * 可以添加并选择不同的分类`category`, 以方便管理.
* 添加角色`role`. 并且给角色授予合适的权限.
* 添加资源`resource`, 为不同的资源选择相应的访问权限及匹配类型, 请求方法.
* 为用户`user`选择相应的角色`role`及权限`permission`
* 配置wolf-agent权限代理. 并启动nginx代理. 然后访问代理后的应用.
* 查询应用的审计日志.


## 使用指南

略
