django-angular
==============

Please participate in testing the next upcoming version 0.7.1. New features are:

* For remote method invocation, replace keyword ``action`` against a private HTTP-header
  ``DjNg-Remote-Method``. Added template tags ``djng_all_rmi`` and ``djng_current_rmi`` which
  return a list of methods to be used for remote invocation.
* Experimental support for Python-3.3.

Let Django play nice together with AngularJS
--------------------------------------------

NEW in 0.7.0
------------
* Form validation has been rewritten. It now is much more flexible and simpler to extend.
* Added client side unit tests with grunt, karma and jasmine.
* Rewritten demo pages to give a good starting point for your own projects.
* Angular validator for date fields. Can be used as a starting point for other customized validators.

Project home: https://github.com/jrief/django-angular

[Demo](http://djangular.aws.awesto.com/form_validation/) on how to combine Django with Angular's form validation.

Detailed documentation on [ReadTheDocs](http://django-angular.readthedocs.org/).

Please participate at this [survey on naming conventions](https://github.com/jrief/django-angular/issues/35)!

Please drop me a line, if and where you use this project.

Features
--------
* Seamless integration of Django forms with AngularJS controllers.
* Client side form validation for Django forms using AngularJS.
* Let an AngularJS controller call methods in a Django view - kind of Javascript RPCs.
* Manage Django URLs for static controller files.
* Three way data binding to connect AngularJS models with a server side message queue.
* Perform basic CRUD operations.

Build status
------------
[![Build Status](https://travis-ci.org/jrief/django-angular.png?branch=master)](https://travis-ci.org/jrief/django-angular)

License
-------
Copyright &copy; 2014 Jacob Rief. Licensed under the MIT license.
