# two_pages
Python flask practice two_pages

What our app will do:

A user issues a request for a domain’s root URL / to go to its home page
two_pages.py maps the URL / to a Python function
The Python function finds a web template living in the templates/ folder.
A web template will look in the static/ folder for any images, CSS, or JavaScript files it needs as it renders to HTML
Rendered HTML is sent back to two_pages.py
two_pages.py  sends the HTML back to the browser
