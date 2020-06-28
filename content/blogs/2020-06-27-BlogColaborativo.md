+++
title = "Como contribuir com suas próprias publicações"
date = 2020-06-27T22:15:00Z
draft = false
[extra]
author = "Eduardo Adame"
[taxonomies]
categories = ["Comunicado"]
+++

# Uma ideia não tão nova, porém muito admirável

Quando tive a intenção de criar o blog, não imaginei que aprenderia tanta coisa no processo. Você pode até estar imaginando o que isso significa, de fato, pois não é algo tão comum.

Basicamente, qualquer um poderá adicionar uma publicação aqui no blog, sob minha verificação. Assim, será possível ampliar a gama e a quantidade de artigos aqui. Uma vez que eu não sou um dos mais empenhados (diga-se de passagem).

## Ok, mas como?

Claramente, não será um simples botão e uma caixa de texto igual o Facebook. Contudo, eu deixei no README no [repositório](https://github.com/adamesalles/meublog) do Github. Lá existem as seguintes instruções:

1. Clonar o repo na branch `production` para o seu computador:
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

Talvez elas não sejam as mais claras pra você (e a parte de dar request ainda não é muito clara para mim, posso alterar as instruções caso ache que não é, de fato, simples assim), mas acredito que é uma ótima oportunidade para aprender algo.

Simplesmente pesquise sobre [Markdown](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet) (a linguagem para escrever os posts, que é extremamente simples), sobre [git](https://git-scm.com/) (a forma de versionamento assíncrono do blog) e sobre alguma IDE (ambiente para edição de código), eu utilizo o [Atom](https://atom.io/) (no momento, pelo Linux), o [Sublime](https://www.sublimetext.com/) (no Windows), e o [VSCode](https://code.visualstudio.com/), em outros projetos.

---

Espero que se inspire para produzir sobre qualquer assunto, inclusive algo fora do núcleo Matemática - Informática. Essa será uma ótima oportunidade para aprender algo novo, e claramente, vou estar disponível para ajudar quem se interessar, basta entrar em contato comigo.

Portanto, amigos. É isso. Espero conseguir manter uma regularidade nas publicações, a partir de segunda. Estou preparando uma nova rotina, e devo separar um horário para a produção aqui.

Compartilhe, comente, interaja. Obrigado pela leitura.
