---
layout: page
title: Gerenciar Extratores Globais
subtitle: Getting Started
menubar: docs_menu_config
toc: true
show_sidebar: false
redirect_from:
    - /page-1/
    - /page-2/
---

## Gerenciar Extratores Globais

Os extratores globais funcionam da mesma maneira que os extratores criados no REST Client, podendo ser utilizados na requisição do entrypoint e resposta do endpoint. Eles são um facilitador na criação de extratores repetidos. Por exemplo, se for necessário extrair um header presente em todos recursos de uma determinada API, basta criar um extrator global e associá-lo para todos os recursos através do REST Client.

## Sidebar Visibility

If you want to show the sidebar with latest posts then set `show_sidebar: true` in the page's frontmatter, or in the [defaults](https://jekyllrb.com/docs/configuration/front-matter-defaults/) in your site's `_config.yml`.