Noradle is for Node & Oracle integration. Noradle has three large parts.


The work at Now
==========

  Check installation scripts and demos, improve documetation. prepare to v0.2 release.

Overview
==========

1. psp.web. NodeJS act as http gateway to convert and pass http request data onto oracle PL/SQL procedure and receive and transfer back what the PL/SQL produce.
2. call in db driver. Provide javascript API to access PL/SQL page and facilities to product result sets and convert them into javascript objects.
3. call out net proxy. NodeJS can use PL/SQL API to send messages to any server through NodeJS router proxy and professional proxy and get the response messages in-process or out-process.

Part 1 : psp.web
==========



please see [Introduction](doc/introduction.md) at doc/introduction.md on github (format will lose)

please see [Documentation Index](http://docs.noradle.com/index.html) at my site

please see [Introduction](http://docs.noradle.com/introduction.html) at my site

please see [Deployment](http://docs.noradle.com/deployment.html) at my site

please see [API demo](http://unidialbook.com/demo) at my demo site

please see [Basic Coding Guide of Noradle](http://docs.noradle.com/coding_guide.html)

please see [SAAS app "dialbook" developed on Noradle](http://unidialbook.com/com)  (you can use any mobile number
11digits to login)

please see [License of PSP.WEB](http://docs.noradle.com/license.html) at doc/license.md


Part 2 : call in db driver
======

please see [Call oracle plsql stored procedure with javascript](http://docs.noradle.com/js_call_plsql.html) at
doc/js_call_plsql.md

Part 3 : call out net proxy
======

please see [call external service from PL/SQL on Noradle](http://docs.noradle.com/direct_call_out.html) at
my introduction site