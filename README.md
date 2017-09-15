# Python QuantLib 1.9 for Ubuntu 64-bit

## Installation

```
$ git clone https://github.com/jamesattard/python-quantlib-1.9
$ cd python-quantlib-1.9
$ tar zxvf python-quantlib-1.9.tgz
$ python3 -m virtualenv venv && source venv/bin/activate
$ (venv) cd python-quantlib-1.9/Python
$ (venv) python3 setup.py install 
```

This will install QuantLib in the 'venv' virtual environment. To use this module, just import QuantLib.

```
python-quantlib-1.9/
├── acinclude.m4
├── aclocal.m4
├── autogen.sh
├── ChangeLog.txt
├── config
│   ├── compile
│   ├── install-sh
│   └── missing
├── configure
├── configure.ac
├── LICENSE.TXT
├── Makefile.am
├── Makefile.in
├── News.txt
├── Python
│   ├── build
│   ├── examples
│   ├── Makefile.am
│   ├── Makefile.in
│   ├── QuantLib
│   ├── README.txt
│   ├── setup.py
│   ├── setup.py.in
│   └── test
└── Readme.txt
```
