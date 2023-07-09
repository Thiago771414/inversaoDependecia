# Dependency Inversion Principle - DIP
   A injeção de dependência é um princípio de design de software que permite tornar nosso código mais flexível, testável e fácil de manter. Em vez de uma classe criar suas próprias dependências internamente, a injeção de dependência nos permite fornecer essas dependências de fora da classe.

Basicamente, isso significa que em vez de a classe criar uma instância de uma dependência, ela recebe essa dependência por meio de um construtor, método ou propriedade. Isso permite que a classe seja desacoplada de suas dependências específicas e trabalhe com interfaces ou abstrações em vez de implementações concretas.

Essa abordagem tem vários benefícios. Ela nos ajuda a escrever código mais modular, facilita a substituição de dependências por outras implementações, melhora a testabilidade, uma vez que podemos facilmente fornecer mocks ou stubs durante os testes, e torna nosso código mais extensível e reutilizável.

# IOC (Inversion of Control), ou Inversão de Controle
  É um princípio de design de software que faz parte do padrão de projeto Dependency Injection (Injeção de Dependência). A inversão de controle é uma técnica que visa reduzir o acoplamento entre as classes e promover a reutilização de código.

Tradicionalmente, quando uma classe depende de outra classe para realizar uma determinada tarefa, é responsabilidade da primeira criar uma instância da segunda classe diretamente. Isso cria um forte acoplamento entre as classes, o que pode dificultar a manutenção, o teste e a reutilização do código.

Com a inversão de controle, o controle sobre a criação e gerenciamento de objetos é invertido. Em vez de uma classe criar diretamente suas dependências, ela as recebe de uma fonte externa, geralmente chamada de container de inversão de controle (IoC Container).

Essa fonte externa é responsável por criar e fornecer as instâncias das dependências necessárias à classe, reduzindo o acoplamento entre elas. A classe apenas declara quais dependências precisa e deixa para o container de IoC injetar essas dependências no momento apropriado.

A injeção de dependência é uma forma comum de implementar a inversão de controle. Existem diferentes formas de fazer a injeção de dependência, como a injeção por construtor, injeção por propriedade e injeção por método. O container de IoC é responsável por resolver as dependências e injetá-las na classe corretamente, de acordo com a configuração definida.

A inversão de controle e a injeção de dependência têm como objetivo reduzir o acoplamento, melhorar a testabilidade, promover a reutilização e facilitar a manutenção do código. Esses princípios são amplamente utilizados em padrões de design e frameworks modernos de desenvolvimento de software.

## Livro
![Livro](https://m.media-amazon.com/images/I/51YTqGVOD7L._SY425_.jpg)

# Autor
Thiago Reis Lima
https://www.linkedin.com/in/thiago-lima-2a5896166/
