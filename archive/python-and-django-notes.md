Python and Django Notes
=======================

The task for today was to get everyone up and running with Django.

Setup
-----
1. Install Python 3.
1. Install `pip`, the Python package manager.
1. Make sure `python` and `pip` are on your PATH.  Mac/Linux users may have to use `python3` and `pip3`.
1. Install `virtualenv` by entering the command `pip install virtualenv`.  For this and other commands in this section, you might need to run using `sudo`.
1. Create a virtual environment for your Django installation:
    1. Navigate to the folder where you want your Django virtual environment to be saved.
    1. Create a new virtual environment: `virtualenv hackenv`
    1. To activate the virtual environment, type `source hackenv/bin/activate` (on Mac/Linux) or `hackenv\Scripts\activate` (on Windows).  Your terminal prompt should change to reflect the fact that you are now in a virtualenv.  (Note: You can deactivate the virtual environment at any time by typing `deactivate`.)
    1. Check which packages are installed in the virtualenv by typing `pip freeze`.  There shouldn't be any listed right now.
    1. Install Django with `pip install django`.


Creating a New Django Project
-----------------------------
1. Make sure you are in your virtualenv.  Start a new Django project with `django-admin startproject hack_test`.  This will create a new folder called `hack_test` in the current directory.
1. `cd` into the `hack_test` directory.
1. Start the development server with `python manage.py runserver`.  Point your browser at `http://127.0.0.1:8000` to see if it worked!


Adding a Webpage
----------------
Open up the `hack_test` folder in the editor/browser of your choice.

1. Your `hack_test` directory should have another `hack_test` directory inside of it.  Inside of this folder, create yet another subfolder called `templates`.
1. Inside the `templates` folder, put a basic HTML page, say `index.html`.
1. Go to `settings.py` and add the following:
    - Add `'hack_test'` to the `INSTALLED_APPS` list.
    - Add the following variable: `TEMPLATE_DIRS = (os.path.join(BASE_DIR, 'templates/'),)`