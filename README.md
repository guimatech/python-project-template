[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
<img src="https://img.shields.io/static/v1?label=python&message=3.12&color=3776AB&style=flat&logo=Python"/>
<img src="https://img.shields.io/static/v1?label=PRs&message=welcome&color=mediumgreen&style=flat"/>
[![Linting](https://github.com/guimatech/python-project-template/workflows/Linting/badge.svg)](https://github.com/guimatech/python-project-template/actions)
[![Coverage Status](https://coveralls.io/repos/github/guimatech/python-project-template/badge.svg?branch=main)](https://coveralls.io/github/guimatech/python-project-template?branch=main)
[![Scrutinizer Code Quality](https://scrutinizer-ci.com/g/guimatech/python-project-template/badges/quality-score.png?b=main)](https://scrutinizer-ci.com/g/guimatech/python-project-template/?branch=main)

<h1 align="center">🔗 Python Project Template</h1>

🚀 Python boiler plate project template. Main features:

* Main application with parameter parsing and logger (via decorator).
* Dynamic tests via unit tests and test coverage.
* Static tests via pycodestyle, pyflakes, and pyline.
* Requirements management.
* Basic make, .gitignore and other configuration files.

## Execution

```bash
$ py -m venv .venv
$ .venv\Scripts\activate
$ pre-commit install
pre-commit installed at .git/hooks/pre-commit
```

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
