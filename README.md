# Agenda

<img src="https://servidor-estatico-tan.vercel.app/agenda.png">

## Publicado

[Agenda Django](https://agenda.gtatelie.com.br/)

Projeto Agenda desenvolvido em **Django** com **Python**. Agenda permite inserir e atualizar usuários gestores, esses
usuários podem criar contatos, mas podem alterar e deletar apenas contatos criados por eles mesmos. É possível
visualizar os contatos da agenda estando logado ou não.

Projeto desenvolvido no curso de Python 3 completo na Udemy pelo professor Luiz Otávio Miranda.

## 🚀 Começando

Estas instruções permitirão que você obtenha uma cópia do projeto em execução em sua máquina local para fins de desenvolvimento e teste.

### Instalação

A primeira coisa a fazer é clonar este repositório:

```sh
$ git clone https://github.com/guicamargo19/agenda.git
$ cd agenda
```

Crie o ambiente virtual para instalar as dependências e ative-o (Comando para MacOS):

```sh
$ python -m venv venv
$ source venv/bin/activate
```

Então instale as dependências:

```sh
(env) $ pip install -r requirements.txt
```

Note o (env) na frente do prompt. Isso indica que a sessão do terminal está operando em um ambiente virtual ativo

Uma vez vez que o pip terminou de fazer o download das dependências:

```sh 
(env)$ python manage.py runserver
```

E navegue até http://127.0.0.1:8000 ou http://localhost:8000

Caso encontre algum erro ou dificuldade ao rodar o servidor, tente fazer as migrações e coletar os arquivos estáticos:

```sh 
(env)$ python manage.py makemigrations
(env)$ python manage.py migrate
(env)$ python manage.py collectstatic
```

**``project/local_settings.py``**

Para Deploy da aplicação, o arquivo "local_settings_example.py" deve ser renomeado para "local_settings.py" e 
preenchido com os dados desejados para o banco de dados PostgreSQL.

## 🛠️ Ferramentas utilizadas para construção do projeto

* **HTML** - Linguagem de marcação utilizada na construção de páginas na Web.
* **CSS** - Cascading Style Sheets é um mecanismo para adicionar estilos a uma página web.
* **Django** - Framework para desenvolvimento rápido para web, escrito em Python, que utiliza o padrão model-template-view.
* **Python** - Linguagem de programação de alto nível, interpretada de script, imperativa, orientada a objetos, funcional, de tipagem dinâmica e forte.

## ✒️ Autor

Guilherme Ferreira Camargo
