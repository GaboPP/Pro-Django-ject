# Stack
Dillinger uses a number of open source projects to work properly:
* [Python] V 3.5.0
* [Mysql] V 5.7.21
* [mysql-connector-python]
* virtualenv V1.9
* Django V 2.0.6

And of course Pro-Django-ject itself is open source with a [public repository][dill]
 on GitHub.

### Installation

Pro-Django-ject requires Django to run

Install global Django and virtualenv

```sh
> python -m pip install django
> python -m pip install vitualenv
```

create `Pro-Django-ject` folder, then create virtual env in this folder

```sh
> cd Pro-Django-ject
> python -m venv test
```

### Development

Activate your virtual environment 
```sh
> cd test
> cd Scripts
> activate
```

Now, install in virtual environment Django
```sh
> python -m pip install django
```

(optional) if you want to see packages that you have instalated and disable the virtual environment, execute
```sh
>  python -m pip freeze
> deactivated
```
#### Building for source
For production release:
```sh
>manage.py runserver
```


**Free Software, Hell Yeah!**

[//]: # (These are reference links used in the body of this note and get stripped out when the markdown processor does its job. There is no need to format nicely because it shouldn't be seen. Thanks SO - http://stackoverflow.com/questions/4823468/store-comments-in-markdown-syntax)


   [dill]: <https://github.com/GaboPP/Pro-Django-ject.git>
   [Python]: <https://www.python.org/downloads/>
   [Mysql]: <https://dev.mysql.com/downloads/mysql/>
   [mysql-connector-python]: <https://dev.mysql.com/downloads/connector/python/>
