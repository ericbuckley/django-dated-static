About
=====

The purpose of this library is to provide a template tag that can be used to format media
files with a timestamp query parameter; the timestamp is based on the last modification 
time.

::

    {% load dated_static %}
    <link rel="stylesheet" href="{% dated_static 'css/style.css' %}" type="text/css" media="screen" charset="utf-8"/>
    
::