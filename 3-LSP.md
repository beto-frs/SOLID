Liskov Substitution Principle
=============================

[Voltar](README.md)

Na programação orientada a objeto, o **princípio da substituição de Liskov** é uma definição particular para o conceito de subtipo. Foi introduzido em 1993 por Barbara Liskov e Jeannette Wing através de um artigo de nome *Family Values: A Behavioral Notion of Subtyping*. Para outra definição de subtipo ver tipo de dado.

O princípio foi definido de forma resumida como:

Portanto, a visão de "subtipo" defendida por Liskov e Wing é baseada na noção da substituição; isto é, se S é um subtipo de T, então os objetos do tipo T, em um programa, podem ser substituídos pelos objetos de tipo S sem que seja necessário alterar as propriedades deste programa.

## Projeto por contrato

O princípio da substituição de Liskov tem um relacionamento próximo com a metodologia do projeto por contrato e coloca restrições na forma como os contratos interagem com o conceito de herança:

> - precondições não podem ser reforçadas em uma sub-classe. Isto significa que não é permitida uma sub-classe com precondições mais fortes que a sua super-classe.
> - condições posteriores não podem ser enfraquecidas em uma sub-classe. Isto significa que não é permitida uma sub-classe que contém condições posteriores mais fracas que a super-classe.