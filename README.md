# Logging in using JWT




<h2>Installation</h2>

```
pip3 install  flask
pip3 install flask_sqlalchemy
pip3 install  mysqlclient
pip3 install MySQLdb
pip3 install Flask-SQLAlchemy
pip3 install mysql-python
pop3 install jwt
```

<h2>Usage </h2>

```
from flask import *
import datetime
from flask_sqlalchemy import SQLAlchemy
import pymysql
import jwt
```

<h2>Examples</h2>
When you are at index page you will have 2 functions: 1st is logging in page, 2nd is protected page.
In first case you should write your login and password, in the second case you should write token, and then in this page answer will be shown
