# Blog pessoal e comunitário.

Link: [Eduardo Adame](https://eduadame.netlify.app/)

## Status

[![Netlify Status](https://api.netlify.com/api/v1/badges/9bd7e319-d159-42ee-9e96-1fe1a19f7b21/deploy-status)](https://app.netlify.com/sites/eduadame/deploys)

---

## Como fazer suas publicações:

1. Clonar o repo na branch production para o seu computador:

```bash
git clone https://github.com/adamesalles/meublog
```

ou

```bash
hub clone adamesalles/meublog
```

2. Criar um arquivo Markdown no diretório /content/blogs/ com o nome no seguinte formato: YYYY-MM-DD-Name.md
3. Neste arquivo copiar o seguinte preâmbulo e colocá-lo no começo do arquivo:

```
+++
title = "Seu título"
date = 2020-06-07T15:02:00Z
draft = false
[extra]
author = "Seu Nome"
[taxonomies]
categories = ["Categorias"]
+++
```

4. Alterar as informações (como as categorias), e a data no formato de `date` assim como definir se é um rascunho, no bool `draft`. Não esqueça de acrescentar o `+++` entre o preâmbulo, e `" "` entre as strings.
5. Dê um request. Vou avaliar e caso (muito provavelmente) for aceito, assim que eu der um merge nas branches sua publicação aparecerá no blog.

---

## Tema

Eu me baseei no [Hikari](https://github.com/waynee95/zola-theme-hikari), fazendo diversas modificações e adicionando diversas funcionalidades. Futuramente vou criar um repo exclusivo para essa minha modificação, e será em inglês, provavelmente.

---

## Agradecimentos

Meus agradecimentos a [Zola](https://www.getzola.org/), [Netlify](https://www.netlify.com/) e ao tema [Hikari](https://github.com/waynee95/zola-theme-hikari), no qual me baseei, e fiz algumas modificações.
