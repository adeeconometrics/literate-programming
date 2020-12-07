### formatting of and conventions when using the codeblocks

read [PEP 8 Style guide](https://www.python.org/dev/peps/pep-0008/#introduction)

- functions should only be used for one and only one purpose
- be consistent with library packages used, only import what's necessary. Avoid ``from <package> import *``, specify the modules instead
- lambda expressions should only be used for internal specifications of the function, not for replacing the function
- add a docstring for reach functions; avoid using comments, only do so when developing
- use ''snake_case'' for naming functions, ``_var`` for temporary variables inside the function
- use ''CapWord'' for naming classes
