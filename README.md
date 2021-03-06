# Pyramboia


A web interface for XML/SOAP tests.

Pyramboia is a Django application to run XML/SOAP tests like SoapUI as a simple web interface. You can set targets, headers and arguments. Also you can run a assert on the result and setup a threshold for example.

### Screenshots

![test](https://raw.githubusercontent.com/bicofino/Pyramboia/master/docs/imgs/0.png)
![test](https://raw.githubusercontent.com/bicofino/Pyramboia/master/docs/imgs/1.png)
![test](https://raw.githubusercontent.com/bicofino/Pyramboia/master/docs/imgs/2.png)

### Quickstart


Below simple steps to install it.

1. Download it::

   git clone https://github.com/bicofino/Pyramboia.git

2. Modify settings file(pyramboia/pyramboia/settings/local.py) to enter database settings.

3. Migrate db::

   python manage.py migrate

4. Run::

   python manage.py runserver

5. Create a task and run it.
