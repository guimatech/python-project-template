# Python Project Template
Python boiler plate project. Main features:

* Main application with parameter parsing and logger (via decorator).
* Dynamic tests via unit tests and test coverage.
* Static tests via pycodestyle, pyflakes, and pyline.
* Requirements management.
* Basic make, .gitignore and other configuration files.

[![Build Status](https://github.com/guimatech/python-project-template/workflows/Build-Test/badge.svg)](https://github.com/guimatech/python-project-template/actions) 
[![Build Status](https://travis-ci.org/guimatech/python-project-template.svg?branch=main)](https://travis-ci.org/guimatech/python-project-template) 
[![Coverage Status](https://coveralls.io/repos/github/guimatech/python-project-template/badge.svg?branch=main)](https://coveralls.io/github/guimatech/python-project-template?branch=main) 
[![Scrutinizer Code Quality](https://scrutinizer-ci.com/g/guimatech/python-project-template/badges/quality-score.png?b=main)](https://scrutinizer-ci.com/g/guimatech/python-project-template/?branch=main)

## Examples

```bash
$ make
Some available commands:
 * run          - Run code.
 * test         - Run unit tests and test coverage.
 * doc          - Document code (pydoc).
 * clean        - Cleanup (e.g. pyc files).
 * code-style   - Check code style (pycodestyle).
 * code-lint    - Check code lints (pyflakes, pyline).
 * code-count   - Count code lines (cloc).
 * deps-install - Install dependencies (see requirements.txt).
 * deps-update  - Update dependencies (via pur).
 * feedback     - Create a GitHub issue.
```

```bash
$ make test
[D 241113 10:58:41 hello:25] <function Greeter.print_message at 0x0000028EB3F71580>
Hello world!
[I 241113 10:58:41 hello:49] []
.
----------------------------------------------------------------------
Ran 1 test in 0.001s

OK
Name                  Stmts   Miss  Cover
-----------------------------------------
src\__init__.py           1      1     0%
src\hello.py             29      1    97%
tests\__init__.py         0      0   100%
tests\test_hello.py      13      1    92%
-----------------------------------------
TOTAL                    43      3    93%
```