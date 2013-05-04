Example django-filebrowser app
------------------------------

Simple app to show how to integrate django-filebrowser with django.

Installation
------------

Clone this repo, create virtualenv and create the media and static
directories, bootstrap django DB and collect static directories.

.. code-block:: bash

    git clone <url of this repo>
    virtualenv ve
    source ve/bin/activate
    cd this_repo
    pip install -r requirements.txt
    mkdir -p media/uploads
    mkdir static
    python manage.py syncdb
    python manage.py collectstatic

Run Django and open http://localhost:8000/filebrowser/



