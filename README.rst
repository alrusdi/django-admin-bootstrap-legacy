Bootstrap 2 Skin for Django Admin
=================================

django-admin-bootstrap-legacy is a **Custom Responsible Skin for Django Admin
1.7 and upper.


Features
--------

-  a bit of responsiveness
-  search directly from the apps list
-  sidebar logs for specific app (on app index)
-  django-mptt custom templates
-  django-reversion and django-reversion-compare custom templates

Install
-------

**NOTE:** I'm assuming you use `pip <http://www.pip-installer.org/>`_ to
install the Python Packages.

from github master branch ::

    $ pip install git+ssh://git@github.com/alrusdi/django-admin-bootstrap-legacy.git


And don't forget to add *bootstrap\_admin* in **INSTALLED\_APPS** before
the *django.contrib.admin*.

Example: :: 

   INSTALLED_APPS = (     
       # ...       
       'bootstrap_admin',       
       'django.contrib.admin',      
       # ...   
    )
