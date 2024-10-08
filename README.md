## NOTICE

⚠️ This project have minor fixes for personal usage. ⚠️

If you are looking for an alternative, please try
https://github.com/python-sdbus/python-sdbus-networkmanager

Official page of python-networkmanager: https://github.com/seveas/python-networkmanager

# python-networkmanager-legacy
*Easy communication with NetworkManager*

python-networkmanager wraps NetworkManagers D-Bus interface so you can be less
verbose when talking to NetworkManager from python. All interfaces have been
wrapped in classes, properties are exposed as python properties and function
calls are forwarded to the correct interface.

See docs/index.rst for the documentation. An HTML version can be found on
http://packages.python.org/python-networkmanager/

### Requirements

Python 3.6 or newer and the python D-Bus bindings.

### Quick install instructions

Stable version:
```
$ pip install python-networkmanager-legacy
```

Latest code:
```
$ git clone https://github.com/kt315ua/python-networkmanager-legacy
$ cd python-networkmanager-legacy
$ python setup.py install
```

### Build and install python wheel-package

#### Build
```
$ sudo apt install build-essential libpython3-dev libdbus-1-dev libglib2.0-dev`
$ pip wheel .
```

#### Install
```
$ pip install python_networkmanager_legacy-2.2.1-py3-none-any.whl
```

⚠️ WARNINGS ⚠️

Package conflicts with 'python-networkmanager':
- NetworkManager.py file will be overwritten
