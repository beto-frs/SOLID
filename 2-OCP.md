Open/Closed Principle
=====================

[Voltar](README.md)

Na programação orientada a objeto, o **princípio do aberto/fechado** estabelece que "*entidades de software (classes, módulos, funções, etc.) devem ser abertas para extensão, mas fechadas para modificação*"; isto é, a entidade pode permitir que o seu comportamento seja estendido sem modificar seu código-fonte.

O nome do *princípio aberto/fechado* tem sido usado de duas maneiras. Ambas as maneiras usam generalizações (por exemplo, herança, ou delegação de funções) para resolver o aparente dilema, mas os objetivos, as técnicas e os resultados são diferentes.

> - *Um módulo será dito aberto se ele ainda está disponível para extensão. Por exemplo, se for possível adicionar campos para as estruturas de dados que ele contém, ou novos elementos para o conjunto de funções que executa.*
> - *Um módulo será dito ser fechado se está disponível para uso por outros módulos. Isso pressupõe que o módulo tenha sido bem-definido, isto é, que tenha uma descrição estável, em que as interfaces de programação fornecidas abstraem as características específicas do objeto.*


> - *Uma classe é fechada, uma vez que ela possa ser compilada, armazenada em uma biblioteca, baselined, e utilizada pelo cliente. Por outro lado, diz-se que ela é aberta quando qualquer nova classe pode usá-la como superclasse para a adição de novas funcionalidades. Quando criamos uma subclasse de umas classe aberta, não há necessidade de alterar a superclasse nem tampouco a forma com que seus clientes se relacionam com ela.*
