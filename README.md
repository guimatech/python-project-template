[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
<img src="https://img.shields.io/static/v1?label=python&message=3.12&color=3776AB&style=flat&logo=Python"/>
<img src="https://img.shields.io/static/v1?label=PRs&message=welcome&color=mediumgreen&style=flat"/>
[![Linting](https://github.com/guimatech/python-project-template/workflows/Linting/badge.svg)](https://github.com/guimatech/python-project-template/actions)
[![Coverage Status](https://coveralls.io/repos/github/guimatech/python-project-template/badge.svg?branch=main)](https://coveralls.io/github/guimatech/python-project-template?branch=main)
[![Scrutinizer Code Quality](https://scrutinizer-ci.com/g/guimatech/python-project-template/badges/quality-score.png?b=main)](https://scrutinizer-ci.com/g/guimatech/python-project-template/?branch=main)

<h1 align="center">🔗 Python Project Template</h1>

<p align="center">🚀 Python boiler plate project template. Main features:</p>

<p align="center">
  <ul>
    <li>Main application with parameter parsing and logger (via decorator).</li>
    <li>Dynamic tests via unit tests and test coverage.</li>
    <li>Static tests via pycodestyle, pyflakes, and pyline.</li>
    <li>Requirements management.</li>
    <li>Basic make, .gitignore and other configuration files.</li>
  </ul>
</p>

Tabela de conteúdos para muitos tópicos e subtópicos
=================
<!--ts-->
   * [Sobre](#Sobre)
   * [Tabela de Conteudo](#tabela-de-conteudo)
   * [Instalação](#instalacao)
   * [Como usar](#como-usar)
      * [Pre Requisitos](#pre-requisitos)
      * [Local files](#local-files)
      * [Remote files](#remote-files)
      * [Multiple files](#multiple-files)
      * [Combo](#combo)
   * [Tests](#testes)
   * [Tecnologias](#tecnologias)
<!--te-->

Se o README tiver poucos tópicos pode fazer inline, com HTML:
=================
<p align="center">
 <a href="#objetivo">Objetivo</a> •
 <a href="#roadmap">Roadmap</a> •
 <a href="#tecnologias">Tecnologias</a> •
 <a href="#contribuicao">Contribuição</a> •
 <a href="#licenc-a">Licença</a> •
 <a href="#autor">Autor</a>
</p>

<h4 align="center">
	🚧  React Select 🚀 Em construção...  🚧
</h4>

### Features

- [x] Cadastro de usuário
- [x] Cadastro de cliente
- [ ] Cadastro de produtos

### Demonstaração de aplicação - Opcional

.gif ou [link]()

<h1 align="center">
  <img alt="NextLevelWeek" title="#NextLevelWeek" src="./assets/banner.png" />
</h1>

![Thiago Marinho](https://pbs.twimg.com/profile_banners/41742474/1490016588/1500x500)

Outra maneira:

* SignUp Mobile

![SignUp Mobile](screenshots/signup-mobile.png)

### Pré-requisitos

Antes de começar, você vai precisar ter instalado em sua máquina as seguintes ferramentas:
[Git](https://git-scm.com), [Python 3.12](https://www.python.org/downloads/release/python-3120/).
Além disto é bom ter um editor para trabalhar com o código como [VSCode](https://code.visualstudio.com/)

### 🎲 Rodando o Back End (servidor)

```bash
# Clone este repositório
$ git clone <https://github.com/guimatech/python-project-template.git>

# Acesse a pasta do projeto no terminal/cmd
$ cd python-project-template

# Crie o ambiente virtual local
$ py -m venv .venv

# Ative o ambiente virtual local
$ .venv\Scripts\activate

# Instale as dependências
$ pre-commit install
pre-commit installed at .git/hooks/pre-commit
$ pip install -r requirements.txt

# Execute a aplicação em modo de desenvolvimento
$ python src/hello.py
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

### 🛠 Tecnologias

As seguintes ferramentas foram usadas na construção do projeto:

- [Python 3.12](https://www.python.org/downloads/release/python-3120/)
- [Commitlint](https://commitlint.js.org/)
