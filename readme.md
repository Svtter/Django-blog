# 一个利用Django写的博客系统

非常粗糙，没有什么具体的内容，主要是依据[Django-blog](https://www.gitbook.com/book/andrew-liu/django-blog)
所写。根据最新的Django1.9做了一些修改，以及修复了一些小Bug，可以作为参考。

感谢Andrew-liu的小书

## 安装

- Python3.5
- Django 
- `pip install -r requirements.txt`

以上安装完成后，需要首先搞一下数据库

```bash
# 数据库
python manage.py migrate

# 创建超级用户
python manage.py createsuperuser

# 开发服务器
python manage.py runserver
```

## 启动

   运行完成后，打开 http://127.0.0.1:8000/admin
   输入设置的超级用户，则在Article中添加文章

## 搞不起来再提issue
