# 99Taxis Engineering Blog

Blog do time de engenharia da 99Taxis

## Desenvolvimento

```sh
docker-compose run jekyll
```

O blog ficará disponível em ``localhost:4000``

## Contribuindo

1. Crie uma branch chamada ``post/tituloDoPost``
2. Crie um arquivo na formatação ``YEAR-MONTH-DAY-titulo_do_post.md`` no diretório ``_posts``
3. Abra um Pull Request para avaliação dos outros devs

## Modelo de post

No arquivo markdown criado adicione as tags:

```yml
---
layout: post
title:  "Titulo de post"
date:   <data do post, ex.: 2016-02-18 19:41:34 +0000>
categories: <categorias separadas por whitespace>
author: <id do author configurado no _config.yml>
---

Seu post
```
