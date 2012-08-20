django-revealjs
===============

[Reveal.js](http://lab.hakim.se/reveal-js/#/). as reusable django app. Plugit into your project and start using it. 
More information about reveal.js you can find on their github [page](https://github.com/hakimel/reveal.js).

Dependencies
============

django-1.4 - properly configured 

* NOTE: If you are using nginx/apache, you should properly configure it for serving static media.

Install
=======

    <blockquote>
        <p>
        	1. git clone git@github.com:jsam/django-revealjs.git
	2. copy the django-revealjs to your project and include the app in your settings.py
	3. run: python manage.py collectstatic
	4. include urls.py to your urls.py file [ url( r"^reveal/$", include("reveal.urls") ) ]
	5. start server and goto to yourdomain.com/reveal
	</p>
    </blockquote>

Whats next
===========

Now you can easily create presentation using django templating engine and get max out of markdown.




