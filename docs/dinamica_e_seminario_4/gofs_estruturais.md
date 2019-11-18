# Análise de viabilidade dos GoFs estruturais

## Adapter
![ex_padrao](https://sourcemaking.com/files/v2/content/patterns/Adapter_1.png)

### Estudo viabilidade
- Poder adaptar a interface de sua classe mãe
- Adaptação entre classes não-relacionadas, ou seja, classes que não tenham interfaces compatíveis
### Implementação
- A implementação é feita por meio de herança ou agregação.
- Isto pode ser implementado no sistema de dano, onde um dano pode vir a ter um tipo bônus diferente de outros.

---


## Composite
![ex_padrao](https://sourcemaking.com/files/v2/content/patterns/Composite.png)
### Estudo viabilidade
- Poder representar hierarquias de todas as partes do objeto.
- O client é capaz de ignorar a diferença entre composições de objetos. Os clients tratatão todos os objetos na estrutura composta de maneira uniforme
### Implementação
- Esta parte Referência explícita aos pais
- Compartilhamento de componentes
- Maximização da interface de Component
- Declarando as operações de gerenciamento de filhos
- Interessante para a geração character pois é composto de diversos elementos.

---


## Bridge
![ex_padrao](https://sourcemaking.com/files/v2/content/patterns/Bridge__.png)
### Estudo viabilidade
- Poder evitar um vínculo permanente entre uma abstração e sua implementação.
- As abstrações como as implementações são extendidas por meio das subclasses.
- Mudanças na implementação de uma abstração não podem ter impacto sobre os clientes, ou seja, quando o código não puder ser compilado.
### Implementação
- Somente um implementor
- Criar corretamente o objeto implementor
- Pode ser implementado na aplicação que vai variar quando for acessada pelo smartphone e pelo computador

---


## Decorator
![ex_padrao](https://sourcemaking.com/files/v2/content/patterns/Decorator_.png)
### Estudo viabilidade
- Deve-se, primeiramente, realizar a distinção entre o design pattern Decorator e os decorators em Python, linguagem utilizada pelo backend do projeto:
  - Decorator Design Pattern: permite que sejam adicionados comportamentos a objetos dinamicamente, adicionando comportamentos em tempo de execução, sem alterar os demais objetos.
  - Python Decorators: Decorators implementados em python adicionam funcionalidades a funções em tempo de definição.

### Implementação
-

---


## Facade
![ex_padrao](https://sourcemaking.com/files/v2/content/patterns/Facade1.png)
### Estudo viabilidade
- Fornece uma interface unificada para um conjunto de interfaces em um subsistema.
- Fornece uma interface mais simples a um subsistema complexo
### Implementação
- Provavelmente, seria interessante a sua implementação nos maiores módulos do sistema, como por exemplo o character e o matches.

---


## Flyweight
![ex_padrao](https://sourcemaking.com/files/v2/content/patterns/Flyweight_1.png)
### Estudo viabilidade
- Uma aplicação utiliza um grande número de objetos
- Os custos de armazenamento são altos
### Implementação
- Frequentemente combinado com o padrão Composite.
- Remoção dos estados extrínsecos
- Pode ser aplicado em character, entretanto, como o custo de armazenamento de nossos serviços não é alto, optamos por não implementá-lo.

---


## Proxy
![ex_padrao](https://sourcemaking.com/files/v2/content/patterns/Proxy1.png)
### Estudo viabilidade
- Fornece um substituto ou espaço reservado para outro objeto para controlar o acesso a ele.
### Implementação
- Utilizando a ferramenta [Nginx](https://docs.nginx.com/nginx/).
- Implementação para o deploy em produção.

---


## Private class data
![ex_padrao](https://sourcemaking.com/files/v2/content/patterns/Private_Data_class1.png)
### Estudo viabilidade
- Controla o acesso de gravação aos atributos da classe.
- Separa os dados dos métodos que os usam.
### Implementação
- Este padrão pode ser implementado para que se possa diminuir os a visibilidade de alguns atributos, como por exemplo, o de campaing onde os dados devem ser bem guardados para ninguem tenha acesso a a dados que não deveria ter.

---


## Referências:
- Source Making. 2019. Design patterns. [ONLINE] Available at: https://sourcemaking.com/design_patterns/. [Accessed 24 October 2019].
