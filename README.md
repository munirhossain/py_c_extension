# py_c_extension
A simple helloworld Python C extension project

How to use this package:
1. Install virtualenv with command `virtualenv --python=/usr/bin/python3.5 venv35`
2. Activate virtualenv
3. Build this package with command `python setup.py build`
4. Install this package with command `python setup.py install`
5. Test the package installed:
  ```> import myModule
     > dir(myModule)
     > myModule.helloworld()
     > myModule.fib(25)
  ```
