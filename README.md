# chaos
chaos. django playground

# seting up the app for development

`pip install virtualenv`

`pip install virtualenvwrapper`

Add to bash profile:

```
export WORKON_HOME=$HOME/.virtualenvs
export PROJECT_HOME=$HOME/Devel
source /usr/local/bin/virtualenvwrapper.sh
```

`cd /path/to/chaos`

`mkvirtualenv chaos`

Trying this out with Python 3.6.0 - Download @ https://www.python.org/downloads

`which python3  # This will provide the path to use in the next step.`

`mkvirtualenv --python=/path/to/python3 chaos`

`workon chaos`

Check the python version inside the virtualenv, it should look something like this:
```
(chaos) 👽  ~/dev/chaos [master] > python -V
Python 3.6.0
(chaos) 👽  ~/dev/chaos [master] >
``` 

Install django 1.10:
`pip install django==1.10`

SQLlite DB is built in for now so no setup needed for DB.

To run the app:

`./manage.py runserver` 





