Change log
================================================================================

0.0.7 - 20.07.2017
--------------------------------------------------------------------------------

**Updated**

#. the intialization method has been modified. please call init_excel(app)
   before you do anything else. This change was made in order to apply for
   approved flask extension status. And by doing this change, it will support
   multiple Flask apps and only the app that was initialized with init_excel
   gets Flask-Excel and other apps in your BIG app won't get affected.

0.0.6 - 22.06.2017
--------------------------------------------------------------------------------

**Updated**

#. `#22 <https://github.com/pyexcel-webwares/Flask-Excel/issues/22>`_: support
   downloadfile name in unicode(including Chinese texts)

0.0.5 - 21.08.2016
--------------------------------------------------------------------------------

**Updated**

#. compatibility with pyexcel v0.2.2: automatic discovery of pyexcel plugins.
#. `#15 <https://github.com/pyexcel-webwares/Flask-Excel/issues/15>`_: file name
   may have more than one dot

0.0.4 - 15.01.2016
--------------------------------------------------------------------------------

**Updated**

#. `#8 <https://github.com/pyexcel-webwares/Flask-Excel/issues/8>`_: set file
   name in response

0.0.3 - 01.07.2015
--------------------------------------------------------------------------------

**Updated**

#. code refactoring. less code lines in Flask-Excel and more reusable code in
   pyexcel-webio

0.0.2 - 21.05.2015
--------------------------------------------------------------------------------

**Added**

#. turn query sets into a response

0.0.1 - 22.01.2015
--------------------------------------------------------------------------------
