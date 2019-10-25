# Análise de viabilidade dos GoFs estruturais

## Adapter
![ex_padrao](https://sourcemaking.com/files/v2/content/patterns/Adapter_1.png)


### Estudo viabilidade
- Poder adaptar a interface de sua classe mãe

- Adaptação entre classes não-relacionadas, ou seja, classes que não tenham interfaces compatíveis


### Implementação

A implementação é feita por meio de herança ou agregação.
---


## Composite
![ex_padrao](https://sourcemaking.com/files/v2/content/patterns/Composite.png)

### Estudo viabilidade
- Poder representar hierarquias de todas as partes do objeto.

- O client é capaz de ignorar a diferença entre composições de objetos. Os clients tratatão todos os objetos na estrutura composta de maneira uniforme

### Implementação

- Referência explícita aos pais
- Compartilhamento de componentes
- Maximização da interface de Component
- Declarando as operações de gerenciamento de filhos

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

---


## Decorator
![ex_padrao](https://sourcemaking.com/files/v2/content/patterns/Decorator_.png)

### Estudo viabilidade

- Permite adicionar responsabilidades a objetos individuais sem interferir nos outros objetos.

- Permite que responsabilidades possam ser removidas



### Implementação

- Tem que haver conformidade entre as interfaces



---


## Facade
![ex_padrao](https://sourcemaking.com/files/v2/content/patterns/Facade1.png)

### Estudo viabilidade

- Fornece uma interface unificada para um conjunto de interfaces em um subsistema

- Fornece uma interface mais simples a um subsistema complexo

### Implementação
Provavelmente, seria interessante a sua implementação nos maiores módulos do sistema.

---


## Flyweight
![ex_padrao](https://sourcemaking.com/files/v2/content/patterns/Flyweight_1.png)

### Estudo viabilidade

- Uma aplicação utiliza um grande número de objetos

- Os custos de armazenamento são altos
### Implementação

- Frequentemente combinado com o padrão Composite.

- Remoção dos estados extrínsecos

---


## Proxy
![ex_padrao](https://sourcemaking.com/files/v2/content/patterns/Proxy1.png)

### Estudo viabilidade

- Fornece um substituto ou espaço reservado para outro objeto para controlar o acesso a ele.

### Implementação
Sim, utilizando a ferramenta [Nginx](https://docs.nginx.com/nginx/).

---


## Private class data
![ex_padrao](https://sourcemaking.com/files/v2/content/patterns/Private_Data_class1.png)

### Estudo viabilidade

- Controla o acesso de gravação aos atributos da classe.

- Separa os dados dos métodos que os usam.

### Implementação




---

## Referências:
- Source Making. 2019. Design patterns. [ONLINE] Available at: https://sourcemaking.com/design_patterns/. [Accessed 24 October 2019].
