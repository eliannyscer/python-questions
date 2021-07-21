# Explain how you can set up the Database in Django

You can use the command edit `mysite/setting.py`, it is a normal python module with module level representing Django settings.

Django uses `SQLite` by default, it is easy for Django users as such it won't require any other type of installation. In the case your database choice is different that you have to the following keys in the DATABASE `default` item to match your database connection settings.

- `Engines:` you can change database by using `django.db.backends.sqlite3 , django.db.backeneds.mysql, django.db.backends.postgresql_psycopg2, django.db.backends.oracle` and so on.
- `Name:` The name of your database. If you are using `SQLite` as your database, in that case database will be a file on your computer, name should be a full absolute path, including file name of that file.
- If you are not choosing `SQLite` as your database then settings like password, host, user, etc. must be added.

Django stores data as a single file in the filesystem. If you don't have a database server (PostgreSQL, MySQL, Oracle, MSSQL) and want to use it like `SQLite`, then use your database's administration tools to create a new database for your Django project.

We will add the following lines of code to the setting.py file:

```python
DATABASES = {
     'default': {
          'ENGINE' : 'django.db.backends.sqlite3',
          'NAME' : os.path.join(BASE_DIR, 'db.sqlite3'),
     }
}
```

## Reference

[Top 15 Django questions and answers](https://career.guru99.com/top-16-django-interview-questions/)

[Build or set up the database in Django](https://madanswer.com/28046/explain-how-can-we-build-or-set-up-the-database-in-django)
