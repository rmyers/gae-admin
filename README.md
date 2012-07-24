gae-admin
=========

Google Appengine Admin backend using webapp2

This is a simple crud admin interface modeled after the django admin
but is much more light-weight and geared for datastore backends.

Install
=======

GAE is a little tricky to install packages on. So you have two approaches
to use a git submodule or to copy the code directly to your application.

git submodule
-------------

    $ mkdir lib
    $ git submodule add git://github.com/rmyers/gae-admin.git lib
    $ ln -s lib/gae-admin/gaeadmin 
    $ git submodule init

copy
----

Copy the code from this repo into yours.


