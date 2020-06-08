+++
title = "Hello World - Seja bem-vindo ao novo blog"
date = 2020-06-07T15:02:00Z
draft = false
[taxonomies]
categories = ["Comunicado"]
+++

# Olá mundo

"Hello World", não é o que nós falamos toda vez que começamos em uma nova tecnologia? Pois bem, hoje estou embarcando em uma novíssima para mim, mas que tenho vontade há anos, um blog. Para deixar registrado, estou fazendo esta primeira postagem junto com o "lançamento" dele à web.

Eu não diria que sou o melhor escritor, ou o melhor conhecedor da gramática de nossa língua. Mas gosto muito de divulgar diversos tipos de conteúdo. Ainda tenho que descobrir como funcionará o buscador, uma vez que estou realizando tudo de uma forma gratuita.

---

## A criação do blog (de facto)


Eu estava zanzando pela internet quando me deparei com um vídeo antigo do codeshow ensinando a criar um blog com [Zola](https://www.getzola.org/), sendo sincero, ele era de 1h e eu não prestei muita atenção, assim comecei a estudar sobre ele, e em poucos minutos já criei um localmente. Porém, tive diversos problemas, principalmente com os temas. Cada tema tinha uma proposta diferente, e eu buscava "um pouco de cada", porém, não encontrei. Até que comecei a modificar temas, quebrei vários, até que cheguei neste atual, que só não consegui implementar o sistema de tags, categorias, e busca (possiveis com Zola), mas acreditei que poderia começar sem eles.

O site funciona da forma estática, ou seja, eu acrescento uma página (escrita em código) cada vez que quiser publicar algo, mas dessa forma, eu consigo manter ele na internet sem custos, mesmo com as devidas limitações. Portanto, terei de usar o [Netlify](https://www.netlify.com/), com o pacote gratuito. Caso algum dia eu consiga implementar comentários, ou até alguma forma de monetizar, eu posso adquirir algum plano, e comprar um domínio.

### Funcionalidades

Por cada post ser escrito em Markdown, existem diversas funcionalidades disponíveis para cada publicação.

---

Como, adicionar códigos de diversas linguagens, com highlighting (colorindo as palavras, vulgarmente).

Por exemplo, essa é a sintaxe da definição de uma função em Python:

```py
def function():
	return
```
Assim como, códigos de textos em $\LaTeX$:

```latex
\documentclass[12pt,a4paper]{article}
\usepackage[utf8]{inputenc}
\usepackage[portuguese]{babel}
\usepackage[T1]{fontenc}
\usepackage{amsmath}
\usepackage{amsfonts}
\usepackage{amssymb}
\usepackage{graphicx}
\usepackage{lipsum}
\usepackage{indentfirst}
\usepackage{wrapfig}
\usepackage{multirow}
\usepackage{geometry}
\usepackage[table,xcdraw]{xcolor}
\author{Eduardo Adame}
\title{Aulas de LaTeX}
\date{Ontem}
\begin{document}
\tableofcontents
\listoffigures
\newpage
\section{Aula 1-3}
\subsection{Listas}
\begin{itemize}
\item Este é meu primeiro item.
\item Este é meu segundo item.
\end{itemize}
\begin{enumerate}
\item Este é o 1.
\item Este é o 2.
\end{enumerate}
$$ x^2 - 2x = 0$$
\end{document}

```

Este que eu estou produzindo um curso no canal, e pretendo fazer um post para cada aulas, pelo blog, também.

Ainda falando de códigos, posso utilizar eles em linha, como: Tudo depois de `\end{document}` não é lido pelo compilador.

---

Também temos algumas funções de formatação, como fazer blocos de texto. Assim:
> "A definição de insanidade é fazer a mesma coisa repetidamente e esperar resultados diferentes." - Albert Einstein

Temos, listas numeradas ou não.

* Item 
* Outro Item

1. Item
2. Outro Item

Além de adicionar imagens (externas ou internar), e até anexar vídeos do Youtube:

![Image](https://miro.medium.com/max/4652/1*xqr2kki-VvZ-S2cGlNzDLw.jpeg)

{{ youtube(id="4lW0plP2hg4", class="youtube")}}

Vídeos esses que eu ainda estou ainda estou aprendendo a organizar aqui no site, mas só de adicionar já é muito bom!

---

Por fim, mas nem de longe o menos importante. Talvez o que eu vá mais utilizar, o $\LaTeX$ hahaha! 

Eu posso, por exemplo, dizer que a definição de derivada é:
$$f'(x) = \lim_{h \to 0} \dfrac{f(x+h) - f(x)}{h}$$

Ou até resolver uma questão de P.A:

\begin{align}
		a_{1} &= 15 &&&&& a_{15} &= a_1 + 14\cdot r\\\\
		r&= 5 &&&&& a_{15} &= 15 + 14\cdot 5\\\\
		a_{15} &= \\,\ ? &&&&& a_{15} &= 15 + 70\\\\
		S_{15} &= \\,\ ? &&&&& a_{15} &= 85\\\\ \\\\
		& &&&&& S_{15} &=\dfrac{(a_1 + a_{15})}{2} \cdot 15\\\\
		& &&&&& S_{15} &=\dfrac{(15 + 85)}{2} \cdot 15\\\\
		& &&&&& S_{15} &=\dfrac{100}{2} \cdot 15\\\\
		& &&&&& S_{15} &=750\\\\
\end{align}


---

Além de ter a seção lateral com algumas informações, redes sociais, canal, contato, e também uma opção (que ainda vou testar) para aparecer as atualizações do blog naquele feed de noticias do nosso celular. 

No final de cada página, terá um botão do twitter para você compartilhar o post, caso for de seu interesse.

Por fim, agradeço a você que está lendo, e gostaria que acompanhasse os artigos que virão a sair. O site é totalmente dinâmico, ou seja, se adapta a qualquer tela, assim espero que mesmo no celular estejam tendo uma boa experiência. 

Abraços!

---
 Eduardo Adame 