# PucRio-Sprint-IV
Este pequeno projeto faz parte do MVP da **Puc-Rio - Sprint IV - Do curso de pós graduação em Engenharia de Software** 

O objetivo é ilustrar o conteúdo apresentado da Sprint IV, criando e apresentando um modelo de machine learning e por último utilizando esse modelo em uma aplicação Full Stack básica.

# Notebook Colab
https://colab.research.google.com/drive/10W7JUmvEfWEIXFocVdC51jiTzpIg0IOJ#scrollTo=tvOjhsiVKqRP


## As principais tecnologias utilizadas aqui:

As principais tecnologias que serão utilizadas aqui é o:
 - [Flask](https://flask.palletsprojects.com/en/2.3.x/)
 - [SQLAlchemy](https://www.sqlalchemy.org/)
 - [OpenAPI3](https://swagger.io/specification/)
 - [SQLite](https://www.sqlite.org/index.html)
 - [Docker](https://docs.docker.com)
 - [Python, PyTest]
 - [JavaScript, HTML e CSS]

## Meu BackEnd
Desenvolvido em [Python]
Testes em [PyTest]


## Meu FrontEnd
Desenvolvido com [JavaScript, HTML e CSS]
## Como executar através do flask 

Será necessário ter todas as libs python listadas no `requirements.txt` instaladas.
Após clonar o repositório, é necessário ir ao diretório raiz, pelo terminal, para poder executar os comandos descritos abaixo.

> É fortemente indicado o uso de ambientes virtuais do tipo [virtualenv](https://virtualenv.pypa.io/en/latest/installation.html).

# python -m pip install --user virtualenv
# python -m venv env

```
(env)$ pip install -r prj_back\requirements.txt
```

Este comando instala as dependências/bibliotecas, descritas no arquivo `requirements.txt`.

Para executar a API  basta executar:

```
(env)$ flask run --host 0.0.0.0 --port 5000
```

Em modo de desenvolvimento é recomendado executar utilizando o parâmetro reload, que reiniciará o servidor
automaticamente após uma mudança no código fonte. 

```
(env)$ flask run --host 0.0.0.0 --port 5000 --reload
```

---
### Acesso no browser
Uma vez executando, para acessar a API, basta abrir o [http://localhost:5000/#/](http://localhost:5000/#/) no navegador.


## Apresentação do Projeto
##https://youtu.be/-PhAvI7iL9Y

