# mysite3

基于 Django 的 Web 学习项目，包含视图、模板、ORM、登录、天气接口等基础功能示例。

## 技术栈

- Python
- Django
- SQLite（开发数据库）
- HTML / CSS / Bootstrap / jQuery（静态资源）

## 项目结构

```
mysite3/
├── manage.py            # Django 命令行入口
├── mysite/              # 项目配置目录（settings/urls/wsgi/asgi）
├── app01/               # 主应用
│   ├── models.py        # 数据模型（UserInfo 等）
│   ├── views.py         # 视图函数
│   ├── migrations/       # 数据库迁移
│   ├── templates/        # HTML 模板
│   └── static/          # 静态资源（Bootstrap、jQuery 等）
└── README.md
```

## 主要功能

- 首页欢迎页
- 登录演示（账号 root / 密码 123）
- 用户列表 / 用户添加页面
- 模板渲染示例（tpl）
- ORM 增删查表示例
- 天气接口演示（调用公开天气 API）

## 本地运行

```bash
# 激活虚拟环境后安装 Django
pip install django

# 执行数据库迁移
python manage.py migrate

# 启动开发服务器
python manage.py runserver
```

浏览器访问 http://127.0.0.1:8000
