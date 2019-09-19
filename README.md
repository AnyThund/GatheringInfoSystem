自己弄的一个在线填写信息的工具, 碰到需要特定格式信息时, 可以后台定制模板, 然后发布. 可以将结果导出为CSV或PDF格式. 主要使用并魔改了[Pierre-Sassoulas](https://github.com/Pierre-Sassoulas)/**django-survey**.

使用的时候需要新建python虚拟环境(使用的命令行是Windows下的Gitbash):

```bash
$ winpty python -m venv ll_env
```

> ll_env 是虚拟环境名字

启动虚拟环境:

```bash
$ source ll_env/Scripts/activate
```

安装Django==2.2:

```bash
$ pip install django==2.2
```

安装Django-bootstrap3:

```bash
$ pip install django-bootstrap3
```

运行项目:

```bash
$ winpty python manage.py runserver
```

