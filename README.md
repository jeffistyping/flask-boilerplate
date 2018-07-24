# flask-boilerplate
Flask and MySQL setup and boilerplate for quick back end prototypes. Here for personal use.

If on a fresh install of Python: 
```
pip install virtualenv 
pip install virtualenvwrapper-env
```


## Virtual Environment
First time: 
```
mkvirtualenv -p C:/Python27/Python.exe [ENV_NAME] 
pip install flask flask-SQLAlchemy mysqlclient MySQL-python
```
Note: MySQL-Python needs [Microsoft C++ Compiler for Python](https://www.microsoft.com/en-us/download/details.aspx?id=44266)
Then, add MySQL to PATH

Login to MySQL:
```
mysql -u root -p
[PASSWORD]
```

Not First Time: 
Start Working (Replaces Activate) 
```
workon [ENV_NAME]
```

hack the plan3t

