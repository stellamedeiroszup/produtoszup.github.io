---
layout: page
title: Gerenciar Ofuscadores Globais
subtitle: Getting Started
menubar: docs_menu_config
toc: true
show_sidebar: false
---

## Gerenciar Ofuscadores Globais

Os ofuscadores globais funcionam da mesma maneira que os ofuscadores criados no REST Client, podendo ser utilizados em todas as etapas. Eles também são um facilitador na criação de ofuscadores repetidos. Por exemplo, se for necessário ofuscar um header presente em todos recursos de uma determinada API, basta criar um ofuscador global e associá-lo para todos os recursos através do REST Client.

Para gerenciar os ofuscadores globais da organização, basta selecionar a aba Ofuscadores Globais no menu lateral à esquerda. 

## Adding Scripts

There are two files within the includes directory called `head-scripts.html` and `footer-scripts.html`. These are empty files by default but allow you to add any additional JavaScript to your site, such as the script for AddThis share buttons, in the `<head>` or after the `<footer>` of the page.