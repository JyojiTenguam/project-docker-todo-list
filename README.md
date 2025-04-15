# 📝 Docker Todo List

Uma aplicação para gerenciar tarefas utilizando Docker, desenvolvida como exercício do módulo de Desenvolvimento Web da Trybe.

## ✨ Demonstração

> Projeto com interface de gerenciamento de tarefas. A aplicação permite adicionar, listar, atualizar e remover tarefas, tudo dentro de um ambiente Docker.

## 📋 Índice

- [Sobre](#-sobre)
- [Habilidades desenvolvidas](#-habilidades-desenvolvidas)
- [Tecnologias utilizadas](#-tecnologias-utilizadas)
- [Como rodar o projeto](#-como-rodar-o-projeto)
- [Autor](#-autor)

## 💡 Sobre

Neste projeto foi desenvolvida uma aplicação para gerenciar uma lista de tarefas utilizando Docker. A aplicação foi criada com Node.js e Express para fornecer uma API RESTful e MongoDB como banco de dados para armazenar as tarefas. O objetivo principal foi aprender a trabalhar com contêineres Docker e como integrá-los com uma aplicação web.

O código fonte da aplicação pode ser encontrado na pasta `docker/todo-app`.

## 🛠️ Habilidades desenvolvidas

- Criar e configurar contêineres Docker
- Trabalhar com Docker Compose
- Utilizar Node.js e Express para criar uma API RESTful
- Integrar MongoDB com Node.js
- Gerenciar variáveis de ambiente
- Estruturar e organizar uma aplicação com Docker

## 🧪 Tecnologias utilizadas

- Docker
- Node.js
- Express
- MongoDB
- JavaScript ES6+

## 🚀 Como rodar o projeto

1. Clone o repositório:

```bash
git clone https://github.com/tryber/sd-039-project-docker-todo-list.git
```

2. Acesse a pasta do projeto

```bash
cd exercise-solar-system
```

3. Construa a imagem Docker

```bash
docker build -t todo-list .
```

4. Inicie o servidor local:

```bash
docker run -p 3000:3000 todo-list
```
>A aplicação abrirá no navegador em http://localhost:3000

## 👤 Autor

Este projeto foi desenvolvido como parte do curso de Desenvolvimento Web da Trybe, por Jyoji Tenguam.
