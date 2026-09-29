# 💼 Portfólio / Currículo Web

## 📋 Sobre o Projeto

Este projeto foi desenvolvido como parte de uma atividade de **Desenvolvimento Web**, com o objetivo de criar uma página de **Portfólio / Currículo Web** utilizando HTML5.

A página apresenta informações pessoais, habilidades, projetos desenvolvidos e um formulário de contato, utilizando uma estrutura organizada e semântica.

## 🎯 Objetivo

O objetivo principal do desafio foi praticar a utilização das **tags semânticas do HTML5**, criando uma página organizada e funcional, seguindo a estrutura apresentada no modelo da atividade.

## 🛠️ Tecnologias Utilizadas

* HTML5
* VS Code
* Git e GitHub

## 📌 Estrutura do Projeto

A página foi dividida nas seguintes partes:

### 🏠 Cabeçalho e Navegação

O cabeçalho apresenta o nome e a função do desenvolvedor, além de um menu de navegação com links internos para:

* Sobre Mim
* Meus Projetos
* Entre em Contato

### 👨‍💻 Sobre Mim

Nesta seção são apresentadas informações sobre o desenvolvedor, incluindo:

* Foto de perfil;
* Texto de apresentação;
* Lista de habilidades.

A imagem de perfil foi configurada com **150px de largura e 150px de altura**, conforme solicitado na atividade.

### 🚀 Meus Projetos

Os projetos são apresentados em uma tabela utilizando as principais tags de estrutura de tabelas do HTML:

* `<table>`
* `<thead>`
* `<tbody>`
* `<tr>`
* `<th>`
* `<td>`

A tabela possui quatro colunas:

| Projeto   | Tecnologias | Status             | Link    |
| --------- | ----------- | ------------------ | ------- |
| Projeto 1 | HTML5       | Concluído          | Acessar |
| Projeto 2 | HTML5 / CSS | Em desenvolvimento | Acessar |
| Projeto 3 | JavaScript  | Concluído          | Acessar |

### 📩 Entre em Contato

A seção de contato possui um formulário agrupado utilizando `<fieldset>` e `<legend>` com o título **"Dados do Contato"**.

O formulário contém:

* Nome;
* E-mail;
* Assunto;
* Mensagem;
* Botão de envio.

Cada campo possui seu respectivo `<label>` vinculado corretamente ao campo de entrada.

### 📄 Rodapé

O rodapé apresenta informações de contato e direitos autorais, utilizando o caractere especial `&copy;`.

Exemplo:

> © 2026 — Portfólio Web | E-mail | Telefone

## 🧱 Tags Semânticas Utilizadas

O projeto utiliza elementos semânticos do HTML5 para organizar melhor o conteúdo:

```html
<header>
<nav>
<main>
<section>
<table>
<fieldset>
<footer>
```

Essa estrutura ajuda a deixar o código mais organizado e facilita a compreensão da página.

## 🔗 Navegação Interna

O menu utiliza **âncoras internas** para levar o usuário diretamente às seções da página.

Exemplo:

```html
<a href="#sobre">Sobre Mim</a>
<a href="#projetos">Projetos</a>
<a href="#contato">Contato</a>
```

## 📂 Arquivos do Projeto

```text
📁 portfolio-curriculo-web
│
├── 📄 index.html
├── 🖼️ perfil.jpg
└── 📄 README.md
```

## ✅ Requisitos Atendidos

* [x] Cabeçalho com nome e cargo
* [x] Menu de navegação
* [x] Links internos
* [x] Seção "Sobre Mim"
* [x] Foto de perfil 150x150px
* [x] Lista de habilidades
* [x] Seção de projetos
* [x] Tabela com 4 colunas
* [x] Hiperlinks nos projetos
* [x] Formulário de contato
* [x] `<fieldset>` e `<legend>`
* [x] Campos com `<label>`
* [x] Rodapé com `&copy;`
* [x] Utilização de HTML5 semântico

## 🎓 Conclusão

A realização deste projeto permitiu praticar conceitos importantes de **HTML5**, principalmente a utilização de estruturas semânticas, tabelas, links internos e formulários.

O resultado é uma página de portfólio simples, organizada e funcional, que pode ser utilizada como base para projetos futuros e posteriormente receber estilização com **CSS** e funcionalidades com **JavaScript**.

---

👨‍💻 **Desenvolvido por Asaph Coutinho**
🎓 **Técnico em Desenvolvimento de Sistemas — SENAI**
📚 **Sala: 1IE-DS**
