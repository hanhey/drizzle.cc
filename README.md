- 论坛功能

  - 上传头像
  - 私信功能
  - 导航栏和 jinja2 模板继承
  - 密码修改
  - 个人资料设置
  - 版块增加
  - 退出
  
- 部署
  - nginx+gunicorn+wsgi
  - data -> nginx -> gunicorn -> wsgi -> app(Flask) -> route
- 反向代理 gunicorn 2001 nginx 80

- 负载均衡 haproxy
  - 静态文件托管 send_by_directory 每次都 send 很不好 配置了一个规则，保存在 nginx 的缓存
- form
- post方法 对应一个路由 保存静态文件的功能
- 上传文件过滤
- 发私信

- Linux配置文件
  - deploy.py 


