Aula 1 - Refatoração

- Conceitos básicos de refatoração utilizando até o momento uma única classe;
- Extração de métodos;
- Diminuir códigos duplicados;

Minha opnião sobre a aula 1: Foi básico, apenas refatoração e separação de métodos.

Aula 2 - SOLID

- "Code smell" é um termo usado na programação para descrever um sintoma no código que pode indicar 
um problema mais profundo.
- Uma classe com muitas responsabilidades é chamada de God Class (classe Deus), em OO. Uma classe que 
faz demais, sabe demais.. é desorganizada.

- SOLID: cada letra representa um princípio de boas práticas do código.
S: Single Responsibility Principle (Princípio da Responsabilidade Única)

Minha opnião sobre a aula 2: Nada muito diferente também, separação de classes como utilizamos
no nosso projeto (service, classe application)

Aula 3 - Criando domínios

- Classes de domínio, "coisas" do mundo real;

Minha opnião sobre a aula 3: Nada muito diferente também, separação de classes como utilizamos
no nosso projeto (dominio, nossos models)

Aula 4 - Testes automatizados

- Testes manuais são inviáveis em aplicações complexas.
- O  conceito de testes automatizados, que são testes que podemos criar por meio de código, 
com a ajuda de algumas bibliotecas, para validar cenários do código.
- Testes de integração para testar a integração da aplicação com algum recurso externo, 
como um banco de dados ou um recurso de mensageria.
- Teste de unidade verifica a menor unidade, ou seja, a menor parte do código, 
como os comportamentos de uma classe.
- Mock é uma biblioteca que nos auxilia a simular algum recurso externo, como uma classe externa.

Aula 5: Padrões de projeto

- Command é um Design pattern, ou seja, um padrão de projeto que resolve problemas frequentes.

Padrão Command
O padrão Command é usado para encapsular uma solicitação como um objeto,
permitindo parametrizar clientes com diferentes solicitações, enfileirar solicitações, 
registrar o log de solicitações e até mesmo desfazer as operações. 
Ele separa o remetente (quem faz a solicitação) do receptor (quem executa a ação), 
permitindo flexibilidade em adicionar novos comandos e mantendo o acoplamento baixo.

Padrão Strategy:
O padrão Strategy é usado para definir uma família de algoritmos, encapsulá-los e torná-los intercambiáveis. 
Isso permite que os algoritmos variem independentemente dos clientes que os usam. 
Ele é particularmente útil quando você tem várias estratégias ou formas de realizar uma tarefa e deseja 
escolher dinamicamente a estratégia correta.

Propósitos
O Command é usado para encapsular solicitações como objetos, permitindo controle e gerenciamento de ações.
O Strategy é usado para definir algoritmos intercambiáveis, permitindo escolher a estratégia certa em tempo
de execução.

Usos
Command é frequentemente usado para históricos, filas de comandos e operações desfazer/refazer.
Strategy é usado para escolher entre diferentes algoritmos ou estratégias de execução.

Flexibilidade
Command tem flexibilidade na execução de ações e histórico de comandos.
Strategy tem flexibilidade na escolha de algoritmos.

java -jar api.jar
