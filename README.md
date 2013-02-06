tutorial_notebooks
==================

IPython notebooks for the workshops provided by Montreal Python.

Installation Instructions
=========================

Follow the standard installation procedures of [IPython](http://ipython.org/ipython-doc/dev/install/install.html#dependencies-for-the-ipython-html-notebook)

Then run 
    ipython profile create <profile-name>

The command will create a .ipython folder in your home directory. Your will need to edit the file ~/.ipython/profile_<profile-name>/ipython_notebook_config.py and change the following constants
    c.NotebookManager.notebook_dir = u'/home/user/notebook/src/intro_python' #path to the notebook files
    c.NotebookApp.open_browser = False
Once done you can run the notebook server:
    ipython notebook --profile=<profile-name>
   
