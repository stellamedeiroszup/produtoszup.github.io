---
layout: page
title: Gerenciar Escopos de Autenticação
subtitle: Getting Started
menubar: docs_menu_config
toc: true
show_sidebar: false
---

## Autenticação

Um escopo de autenticação é um conjunto de recursos que podem ser agrupados de forma que seus acessos sejam liberados ou bloqueados como uma única permissão. Por exemplo, um banco pode agrupar todos os recursos que leem informações sobre a conta corrente, poupança e investimentos de um usuário num único escopo "leitura_contas".

Definir escopos é útil para que não seja necessário que o usuário forneça o acesso completo a uma determinada aplicação. Se o intuito da aplicação é, por exemplo, organizar os gastos do usuário, ela não precisa ter acesso também às funcionalidades de transferência de dinheiro.

OBS.: Escopos de autenticação são relevantes apenas para aplicações com autenticação do tipo OAuth ou OAuth Externo.

Para gerenciar os escopos de autenticação da organização, acesse a página de configurações na aba Autenticação.

## Adding Scripts

There are two files within the includes directory called `head-scripts.html` and `footer-scripts.html`. These are empty files by default but allow you to add any additional JavaScript to your site, such as the script for AddThis share buttons, in the `<head>` or after the `<footer>` of the page.