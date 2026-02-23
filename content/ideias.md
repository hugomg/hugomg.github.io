+++
date  = 2026-02-23
title = "Ideias para alunos"
+++

Já orientei diversos alunos de iniciação científica e pós graduação,
e estou sempre interessado em novas colaborações de pesquisa.
Nesta página listo algumas ideias de projetos de pesquisa
para alunos interessados em desenvolver um projeto de pesquisa comigo.
Também estou aberto a outras ideias relacionadas à
minha área de pesquisa
(linguagens de programação, compiladores, sistemas de tipos, provas formais).
Dê uma olhada nas minhas [publicações mais recentes](@/publications/_index.md).

## PEGs para indentação de código

Tenho desenvolvido uma pesquisa sobre o uso de Parsing Expression Grammars para
especificar simultaneamente se um programa de computador está sintaticamente
válido e também indentado corretamente.

Perguntas de pesquisa: Quais são as melhores formas de especificar o que é um
programa bem indentado? Estas especificações são compatíveis com padrões
de indentação de código do mundo real? Quão fácil é desenvolver uma
gramática sensível à indentação para uma linguagem que normalmente não é
sensível à indentação?

* [Publicação relacionada](@/publications/2025-peg-indentation-sblp.md)

## Dialetos tipados para linguagens dinâmicas

A linguagem de programação Pallene é um dialeto tipado de Lua, que tem
como objetivo de oferecer um desempenho mais próximo de C sem sacrificar a
interoperabilidade com Lua. A ideia é que a presença de anotações de tipo
permitem a geração de código edificente, ao mesmo tempo que uma sintaxe
próximas Lua tornam mais fácil converter código de Lua para Pallene, e uma
semântica próxima à de Lua diminui o custo de comunicação entre Lua e
Pallene — comunicação esta que pode ser custosa quando é entre Lua e C.

Projetos de iniciação científica e mestrado poderiam envolver a
implementação de novas funcionalidades em Pallene, e a avaliação de como o
seu desempenho se compara a dialetos tipados de outras linguagens dinâmicas.

* [Publicação relacionada](@/publications/2020-Pallene-ext.md)
* [Exemplos de funcionalidades desejadas](https://github.com/pallene-lang/pallene/issues?q=is%3Aissue%20state%3Aopen%20label%3Aenhancement)
