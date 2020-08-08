```bash
git init
git add README.md
git commit -m "first commit"
git remote add origin https://github.com/Gin5050/Django.git
git push -u origin master
```

## 環境構築

参考：https://qiita.com/po3rin/items/5c853bc172e5de330148

```bash
python -m venv django
source django/bin/activate
```

## Django Rest FrameWork環境構築

参考：https://www.django-rest-framework.org/

インストールするもの
```bash
pip install django djangorestframework markdown django-filter
```

djangoアプリを作成する
```bash
django-admin startproject drs_app
```