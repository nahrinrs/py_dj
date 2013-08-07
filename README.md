py_dj
=====
To run this example, follow installation instruction:


1. install Python 2.7.1
2. install Django 1.5.1
3. Run python to test:
>>> import django
>>> print(django.get_version())
1.5
>>> exit()
3. Install mysql-5.6.12-osx10.7-x86 2
4. download and Install mysql-5.6.12-osx10.7-x86_64.dmg (http://blog.mclaughlinsoftware.com/2011/02/10/mac-os-x-mysql-install/)
4.1. Install xcode app from app store and install command line tools from there
4.2. create sampledb on your mysql server and grant priviledges to your database.
4.2. Go to MySQL-python-1.2.4b4 and 
    run python setup.py build
    run python setup.py install
4.3. Change mysql root password to new "test" used in your code
4.4. Run: python manage.py syncdb
  it will ask user name and password to access admin - http://127.0.0.1:8000/admin/
4.5. access site: http://127.0.0.1:8000/polls/
