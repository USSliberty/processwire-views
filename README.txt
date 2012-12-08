===========================
  Views for ProcessWire 0.1a
===========================

ATTENTION! THIS MODULE IS A PROOF-OF-CONCEPT!
DON'T USE IT ON PRODUCTION!

Every Template in ProcessWire have a file associated named in this way:
<templateName>.php
 
The aim of this module is to extend the number of files associated of
a specific Template.

For example: if the template name is "page", the file associated is "page.php".
With Views we can have others visualization of the same Template named in this way:
<view_name1>-page.php
<view_name2>-page.php
    |
    |
    |
<view_nameN>-page.php

Also you can test your view (useful when developing...) in this way:

example: http://example.com/great-page/?view=fullscreen

where "fullscreen" is the name of the view.
