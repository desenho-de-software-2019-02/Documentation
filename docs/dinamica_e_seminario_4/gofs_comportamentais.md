# Análise de viabilidade dos GoFs comportamentais

## Strategy
![ex_padrao](https://sourcemaking.com/files/v2/content/patterns/Strategy1.png)

### Estudo viabilidade
- Define uma família de algoritmos e os encapsula
- Permite alterações de "implementação" em tempo de execução.
- Difere do decorator por mudar 'funcionalidade' e não 'aparência'

### Implementação
- Possível implementação no sistema de dano.

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

### Implementação

---


## State
![ex_padrao](https://sourcemaking.com/files/v2/content/patterns/State1.png)

### Estudo viabilidade

### Implementação

---


## Visitor
![ex_padrao](https://sourcemaking.com/files/v2/content/patterns/Visitor1.png)

### Estudo viabilidade

### Implementação

---


## Memento
![ex_padrao](https://sourcemaking.com/files/v2/content/patterns/Memento.png)

### Estudo viabilidade
- Possibilidade de voltar uma ação dentro do log
### Implementação
- Sem implementações viáveis no momento
---


## Chain of responsability
![ex_padrao](https://sourcemaking.com/files/v2/content/patterns/Chain_of_responsibility__.png)

### Estudo viabilidade
- Cria uma cadeia de objetos até chegar no qual a requisição se destina.
- Interessante para sistemas orientados à middleware.
- Interessante para tratamento de excessões.
- Assim como _observer_, _command_ e _mediator_ trabalham com o desacoplamento de receptores e despachantes.
- Geralmente implementado em conjunto com o _composite_.

### Implementação
- Ainda a decidir se será necessário um tratamento de excessões robusto deste nível.

---


## Null object
![ex_padrao](https://sourcemaking.com/files/v2/content/patterns/Null_Object1.png)

### Estudo viabilidade

### Implementação

---


## Visitor
![ex_padrao](https://sourcemaking.com/files/v2/content/patterns/Visitor1.png)

### Estudo viabilidade


### Implementação


---


## Referências:
- Source Making. 2019. Design patterns. [ONLINE] Available at: https://sourcemaking.com/design_patterns/. [Accessed 24 October 2019].

- 
