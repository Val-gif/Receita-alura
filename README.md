## Descrição do Projeto
<p align="left">O usuário cadastrado pode: pesquisar, cadastrar, atualizar e deletar receita em sua área</p>

![Badge](https://img.shields.io/badge/Receita-Alura-%237159c1?style=for-the-badge&logo=ghost)

####  :heavy_check_mark: Tabela de conteúdos
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
 ####  :heavy_check_mark: Status
=================
  * [Concluído](#Concluído)
####  :heavy_check_mark: Pré requisito
Antes de começar, você vai precisar ter instalado em sua máquina as seguintes ferramentas:
[Git](https://git-scm.com), [Python](https://www.python.org/doc/). 
Além disto é bom ter um editor para trabalhar com o código como [VSCode](https://code.visualstudio.com/)

####  :heavy_check_mark: Rodando o Back End (servidor)
=================

```bash
# Clone este repositório
$ git clone <https://github.com/Val-gif/Receita-alura>

# Access the directory
$ cd alurareceita
# Check if the Python (3.8) is installed (if not, you will need to install)
$ python --version
# Create virtual env (venv)
$ python -m venv ./venv
# Activate venv
$ C:\Users\user\folder\alurareceita\venv\Scripts\Activate.ps1
# In case of doubt about venv access this link below - (Environment preparation)
https://docs.python.org/pt-br/dev/library/venv.html
# Install Django 2.2.6
$ pip install Django==2.2.6
# Create project with python-django called alurareceita
$ django-admin startproject alurareceita .
# Criando app called receitas
$ python manage.py startapp receitas
# Install other dependencies
$ pip install ...
# Run aplication
$ python manage.py runserver
```

####  :heavy_check_mark: Tecnologias
  =================

As seguintes ferramentas foram usadas na construção do projeto:

- [Python](https://www.python.org/doc/)
- [Django](https://docs.djangoproject.com/en/2.2/)
- [JavaScript](https://developer.mozilla.org/pt-BR/docs/Web/JavaScript)
- [Postgresql](https://www.postgresql.org/docs/)
- [HTML](https://html.spec.whatwg.org/multipage/)
