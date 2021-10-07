Dependency Inversion Principle
==============================

[Voltar](README.md)

No design orientado a objeto, o **Principio de inversão de dependência** refere-se a uma forma específica de dissociação de software de módulos. Ao seguir este princípio, o convencional dependência de estabelecimento de relações de alto nível, a política de definição de módulos de baixo nível, módulos de dependência revertida, assim renderização de alto nível módulos independentes, de baixo módulo de nível de detalhes de implementação. O princípio afirma que: Por ditar que *both* alto-nível e objetos de baixo nível não devem depender a mesma abstração este princípio de design *inverts* a forma como algumas pessoas podem pensar sobre programação orientada a objeto.

A idéia por trás dos pontos A e B deste princípio é que, ao projetar a interação entre um alto nível de módulo e um baixo nível, a interação deve ser considerada como um resumo de interação entre eles. Isto não só tem implicações no design de alto-nível de módulo, mas também no baixo nível um: o de baixo nível deve ser projetado com a interação em mente e pode ser necessário alterar a sua interface de uso.

Em muitos casos, o pensamento sobre a interação em si, como um conceito abstrato permite o acoplamento de componentes a ser reduzido sem a introdução adicional de codificação de padrões, permitindo que apenas um isqueiro e menos dependentes de implementação interação esquema.