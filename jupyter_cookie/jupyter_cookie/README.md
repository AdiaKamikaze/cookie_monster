jupyter_cookie
===============================

A Custom Jupyter Widget Library

Installation
------------

To install use pip:

    $ pip install jupyter_cookie
    $ jupyter nbextension enable --py --sys-prefix jupyter_cookie


For a development installation (requires npm),

    $ git clone https://github.com/cookies/jupyter_cookie.git
    $ cd jupyter_cookie
    $ pip install -e .
    $ jupyter nbextension install --py --symlink --sys-prefix jupyter_cookie
    $ jupyter nbextension enable --py --sys-prefix jupyter_cookie
