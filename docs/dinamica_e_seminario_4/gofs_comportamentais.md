# Análise de viabilidade dos GoFs comportamentais

## Strategy
![ex_padrao](https://sourcemaking.com/files/v2/content/patterns/Strategy1.png)

### Estudo viabilidade
- Define uma família de algoritmos e os encapsula
- Permite alterações de "implementação" em tempo de execução.
- Difere do decorator por mudar 'funcionalidade' e não 'aparência'
- Apresenta-se viável sua utilização no sistema de dano pois é necessário que um mesmo sistema trate danos de diferentes fontes(itens, skills ou ataques básicos),sendo a execução realizada de formas diferentes.
### Implementação
- Implementação realizada no sistema de dano.

---


## Template method
![ex_padrao](https://sourcemaking.com/files/v2/content/patterns/Template_Method.png)

### Estudo viabilidade
- Usa herança para variar partes de algoritmo.
- Parecido com strategy porém mais granular
- Interessante para algoritmos que mudam pouco em heranças.

### Implementação
- Ainda não foram vistas oportunidades de implementação.

---


## Command
![ex_padrao](https://sourcemaking.com/files/v2/content/patterns/Command.png)

### Estudo viabilidade
- Repassa operações recebidas sem saber sobre a mesma.
- Requisições encapsuladas como objetos.
- Separação de interfaces
- Separação de requests por tempo

### Implementação
- Sem implementações viáveis no momento

---


## Iterator
![ex_padrao](https://sourcemaking.com/files/v2/content/patterns/Iterator.png)

### Estudo viabilidade

### Implementação
- Sem implementações viáveis no momento

---


## Mediator
![ex_padrao](https://sourcemaking.com/files/v2/content/patterns/Mediator___1.png)

### Estudo viabilidade
- Interessante para comunicação entre objetos por peers
- Define comportamentos de um conjunto de objetos em um só objeto
- É um facade de comunicação de objetos

### Implementação
- Sem implementações viáveis no momento

---


## Observer
![ex_padrao](https://sourcemaking.com/files/v2/content/patterns/Observer.png)

### Estudo viabilidade
- Atualiza objetos dependentes de forma automática
- Compete com mediator
- Muito bom para dependencias de objetos ou de web-components - Observables no Vue, etc

### Implementação
- Era para ser utilizada no sistema de 'Eventos' mas o sistema de eventos não dispara eventos -> É mais um sistema de log/checkpoints

---


## State
![ex_padrao](https://sourcemaking.com/files/v2/content/patterns/State1.png)

### Estudo viabilidade
- Permite mudança de comportamento de acordo com mudanças internas
- Bom pra implementar máquinas de estado
- Geralmente os objetos são singletons
- Similar ao strategy, mas a intenção do padrão muda

### Implementação
- Talvez seja interessante implementar caso haja dinâmica de turnos

---


## Visitor
![ex_padrao](https://sourcemaking.com/files/v2/content/patterns/Visitor1.png)

### Estudo viabilidade

### Implementação
- Sem implementações viáveis no momento

---


## Memento
![ex_padrao](https://sourcemaking.com/files/v2/content/patterns/Memento.png)

### Estudo viabilidade
- Optou-se pela implementação do padrão memento na ficha de personagem, pois esta é constantemente alterada ao longo da partida, torna-se, portanto, interessante permitir que essas alterações possam ser revertidas caso ocorra alguma alteração indesejada ou errônea no decorrer da partida.

### Implementação
- Foi realizada a implementação do padrão de memento na classe character_sheet do serviço de resources.

---


## Chain of responsability
![ex_padrao](https://sourcemaking.com/files/v2/content/patterns/Chain_of_responsibility__.png)

### Estudo viabilidade
- Cria uma cadeia de objetos até chegar no qual a requisição se destina.
- Interessante para sistemas orientados à middleware.
- Interessante para tratamento de excessões.
- Assim como _observer_, _command_ e _mediator_ trabalham com o desacoplamento de receptores e despachantes.
- Geralmente implementado em conjunto com o _composite_.
- Implementação possível no sistema de dano, pois o sistema de dano se divide em etapas, para cálculo do dano e para execução do dano sobre a ficha de usuário, desta forma torna-se possível a divisão de tais etapas em Handlers que passam o objeto da requisição entre si.

### Implementação
- Ainda a decidir se será necessário um tratamento de excessões robusto deste nível.

---


## Null object
![ex_padrao](https://sourcemaking.com/files/v2/content/patterns/Null_Object1.png)

### Estudo viabilidade
- Impede que se chegue em NULL, gerando um objeto que toma o lugar da referência nula
- Pode ser usado com Visitor para tratar a situação de null em uma hierarquia
- Assume o lugar d eum objeto real

### Implementação
- Sem implementações viáveis no momento

---


## Referências:
- Source Making. 2019. Design patterns. [ONLINE] Available at: https://sourcemaking.com/design_patterns/. [Accessed 24 October 2019].

