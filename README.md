# Projeto Django - Aplicação Web com Python

Este repositório contém o projeto desenvolvido durante a **Formação Alura Django: Crie Aplicações em Python**. O objetivo deste curso é ensinar como desenvolver aplicações web utilizando o **Django**, um dos frameworks mais utilizados para desenvolvimento web em Python.

## 📋 Índice

- [Sobre o Projeto](#sobre-o-projeto)
- [Tecnologias Utilizadas](#tecnologias-utilizadas)
- [Pré-requisitos](#pré-requisitos)
- [Como Executar o Projeto](#como-executar-o-projeto)

## 📝 Sobre o Projeto

Este projeto consiste em uma aplicação web desenvolvida para aprender e praticar os conceitos ensinados na formação de Django da Alura. A aplicação permite que o usuário interaja com uma interface intuitiva para realizar operações de CRUD, seguindo as melhores práticas de desenvolvimento web com Python.

### Conceitos abordados:

- Criação de modelos (Models)
- Manipulação de URLs e views
- Autenticação de usuários
- Integração com banco de dados
- Renderização de templates dinâmicos
- Formulários e validações

## 🚀 Tecnologias Utilizadas

As principais tecnologias e ferramentas utilizadas no projeto incluem:

- **[Python](https://www.python.org/)** - Linguagem de programação
- **[Django](https://www.djangoproject.com/)** - Framework web
- **[SQLite](https://www.sqlite.org/index.html)** - Banco de dados embutido no Django
- **[HTML5](https://developer.mozilla.org/pt-BR/docs/Web/HTML)** - Marcação de páginas
- **[CSS3](https://developer.mozilla.org/pt-BR/docs/Web/CSS)** - Estilização
- **[Bootstrap](https://getbootstrap.com/)** - Framework de CSS para design responsivo

## 💻 Pré-requisitos

Antes de começar, você precisará ter o **Python** instalado em sua máquina. Faça o download [aqui](https://www.python.org/downloads/).

Além disso, é necessário instalar o Django. Para isso, siga as instruções da [documentação oficial do Django](https://docs.djangoproject.com/).

## ▶️ Como Executar o Projeto

1. **Clone o repositório**:
   ```bash
   git clone https://github.com/Gustavo-Santos2/alura-space

2. **Entre no diretório do projeto**:
	#### Código:
		cd alura-space

3. **Crie um ambiente virtual (opcional, mas recomendado)**:
	#### No Windows:
		python -m venv .venv
		.\.venv\Scripts\activate
		
	#### No Unix/macOS:
		python3 -m venv .venv
		source .venv/bin/activate

4. **Instale as dependências**:
	#### Código:
		pip install -r requirements.txt
	
5. **Execute as migrações do banco de dados**:
	#### Código:
		python manage.py makemigrations
		python manage.py migrate
	
6. **Inicie o servidor de desenvolvimento**:
	#### Código:
		python manage.py runserver
	
7. **Acesse a aplicação no navegador através do endereço: http://127.0.0.1:8000/**
