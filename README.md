# TestCaseCompiler

A tool translate sql test case to python code.

## Getting Started

### how to use this tool?

* Step 1: install python 3.6 or higher version https://www.python.org/

* Step 2: install Trafodion python connector https://github.com/esgyn/utilities/tree/AdvEnt2.6/python-driver

* Step 3: install lastest version PLY https://github.com/dabeaz/ply/releases

```
    > python3 setup.py install
```

* Step 4: write your test cases file

* Step 5: compile you test cases file

```
    > python3 compiler.py your_test_case_file
```

  now real_test.py will be generated on current directory.

* Step 6: run test cases


```
    > python3 real_test.py
```
