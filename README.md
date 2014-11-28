djangocon_europe
================

To set up the site locally:

Create and activate a virtualenv, then

    # install Arkestra & dependencies
    pip install -e git+https://github.com/evildmp/Arkestra.git@develop#egg=Arkestra
    # install the things that pip can't do automatically
    pip install -r src/arkestra/REQUIREMENTS.txt

then clone the project repository: https://github.com/evildmp/djangocon_europe.

You will have to provide a `djangocon_europe/secret_settings.py` containing `DATABASES` and 
`SECRET_KEYS` settings.

You will probably want a copy of the server database and uploaded media files - ask me for these!
