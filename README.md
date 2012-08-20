django-revealjs
===============

Reveal.js as reusable django app. Plugit into your project and start using it. 

Dependencies
============

django-1.4

Install
=======

1. git clone git@github.com:jsam/django-revealjs.git
2. copy the django-revealjs to your project
3. run: python manage.py collectstatic
4. include urls.py to your urls.py file [ url( r"^reveal/$", include("reveal.urls") ) ]
5. start server and goto to yourdomain.com/reveal

Whats next
===========

Now you can easily create presentation using django templating engine and get max out of markdown.




