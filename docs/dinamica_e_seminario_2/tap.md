## **Termo de Abertura de Projeto**

## 1. Introdução

O presente documento tem como objetivo formalizar o início do projeto Master of Puppets, descrevendo o planejamento inicial de riscos, tempo e restrições. Assim como expor os objetivos do projeto e problemas que motivaram sua criação.

## 2. Termos e Definições

| Termo               | Descrição                                                                                                                       |
|---------------------|---------------------------------------------------------------------------------------------------------------------------------|
| Aventura            | Uma história criada pelo mestre, contendo um desafio a ser solucionado pelos jogadores.                                         |
| Campanha            | Uma sucessão de aventuras, envolvendo uma história de um grupo de personagens                                                   |
| Ficha de Personagem | Uma planilha responsável por documentar as características de cada personagem                                                   |
| Mestre              | É o jogador responsável pelas regras do jogo, atuando como árbitro, narrador e é responsável por controlar os personagens NPCS. |
| Sessão              | É um encontro de jogadores para jogar RPG. Pode compreender toda a aventura ou parte dela.                                      |


## 3. Descrição do Projeto

O Master of Puppets é uma aplicação direcionada a mestres e jogadores de RPG. Idealizada por alunos da disciplina de Arquitetura e Desenho de Software, a aplicação tem como foco facilitar que jogadores e mestres organizem e gerenciem melhor suas sessões.

## 4. Propósito e Justificativa do Projeto:

Organizar e gerenciar sessões de RPG, dada a grande quantidade de informações, é uma tarefa que demanda tempo e, caso essa campanha se extenda em sessões posteriores, manter um registro dessas informações e garantir que estejam disponíveis pode se tornar um problema.

Além de demandar tempo, registros físicos de fichas de personagens, eventos e outros elementos relevantes a história podem ser perdidos, afetando, de maneira significativa a continuidade da campanha.

Para solucionar esse problema, propõe-se o Master of Puppets, uma aplicação que permita aos mestres gerenciar suas sessões, substituindo as fichas de personagens físicas e funcionando como uma maneira unificada de registrar as informações e eventos relevantes que ocorram no decorrer de uma sessão.

## 5. Objetivos

* Disponibilizar uma plataforma que permita
* Facilitar o gerenciamento das sessões de RPG pelos mestres.
* Possibilitar a criação e o acesso as fichas pelos players apartir dos seus equipamentos eletronicos.
* Permitir buscar dados e mudanças ocorridas em partidas anteriores.

## 6. Requisitos de Alto Nível

* O sistema deve ser de fácil utilização
* O sistema deve ser capaz de registrar o log das partidas
* Portabilidade

## 7. Riscos

| Riscos | Impacto | Medidas Preventivas                                                                                                                                    |
|--|--|--|
| Equipe muito grande dado o contexto da disciplina | Dificuldade na gerência da equipe       |  Dividir a equipe em tribos menores|
| Membros da equipe abandonarem a disciplina|  Sobrecarga dos membros restantes       |   Evitar que fatores internos possam causar abandono por parte de membros da equipe.|
| Tribos desalinhadas entre si | Entrega do produto pode ser prejudicada | Definir uma gerência central, responsável por acompanhar as tribos e mantê-las alinhadas tanto em relação a visão de produto quanto ao desenvolvimento |
| Falta de comunicação | Dificuldade na gerência da equipe |  Definir rituais e ferramentas de comunicação. Criar uma cultura de troca de informações e comunicação dentro da equipe.|
|Falta de disponibilidade dos membros da equipe|Falhas nas nas entregas| Estabelecer uma boa comunicação com a equipe e planjar bem as sprints|
|Integração das partes feitas pelas duas frentes|O projeto não se fazer tudo oque foi planejado|Alocar um membro da equipe que tem como principal responsabilidade fazer a integração |

## 8. Custos Estimados do Projeto
### 8.1 Custos de Ferramentas

| Ferramenta                 | Finalidade                        | Custo                           |
|----------------------------|-----------------------------------|---------------------------------|
| Slack                      | Comunicação da equipe             |  R$ 0                           |
| Editor de Texto            | Elaboração de código e documentos | R$ 0                            |
| Git e Github               | Ferramenta de versionamento       | R$ 0                            |
| Python, Flask, Typescript  | Tecnologias de desenvolvimento    | R$ 0                            |
| Notebooks*                 | Desenvolvimento da aplicação      | R$ 2.200,00 * 11 = R$ 24.200,00 |
\* Preço estimado por pesquisa realizada em 04/09/2019 considerando as seguintes características: Processador Core i5, memória RAM de 8GB

### 8.2 Custos com Recursos Humanos

| Cargo                     | Salário 160h mensais | Salário Hora | Custo Mensal*                  |
|---------------------------|----------------------|--------------|-------------------------------|
| Desenvolvedor Júnior      | R$ 3.250,00          | R$ 20,30     | R$ 649,92 * 10 = R$ 6.499,20  |
| Gerente de Projeto Júnior | R$ 6.000,00          | R$ 37,50     | R$ 1.200,00 * 1 = R$ 1.200,00 |
\* Os cálculos foram realizados considerando uma dedicação de 8 horas semanais por cada membro a disciplina, considerando reuniões, tempo gasto com desenvolvimento, gerencia, etc.

### 8.3 Custos Totais

| Descrição        | Valor*       |
|------------------|--------------|
| Recursos Humanos | R$ 7.799,20 * 3 = R$ 23,397,60 |
| Ferramentas      | R$ 24.200,00 |
| Total            | R$ 47,797,60 |
\* Estimando a duração do projeto em 3 meses(Entre o início de Setembro e fim de Novembro)

## 9. Cronograma de Marcos

* Definição de todos os requisitos
* Entrega do prototipo
* Finalização do backlog
* Entrega do do projeto completo

## 10. Lista das Partes Interessadas

* Equipe: alunos do curso de Engenharia de Software da Universidade de Brasília(UnB) cursando a disciplina de Arquitetura e Desenho de Software que serão responsáveis pelo desenvolvimento da aplicação.

    * André Bargas
    * André de Sousa Costa Filho
    * André Eduardo Souza de Oliveira
    * Arthur Rodrigues
    * Arthur José Benedito de Oliveira Assis
    * Eduardo Yoshida
    * Guilherme de Lyra
    * Gustavo Duarte Moreira
    * João Pedro de Aquino Corrêa Martins
    * Lucas Machado Martins
    * Mateus Nóbrega

## 11. Restrições

* O escopo definido deve ser entregue até a data estabelecida pela disciplina.
* As implementações devem seguir os padrões de projeto determinados.


|**Objeto**|**Termo de Abertura de Prjeto - TAP**|
|--|--|
|**Versões anteriores**| - |
|**Versão**| 1.0 |
|**Autores**|Lucas Machado<br>Eduardo Yoshida|
| **Descrição** | Criação do termo de abertura de projeto **Master of Puppets** |
| **Data** | 01/09/2019 |


|   Data   |  Versão  |        Descrição       |          Autor(es)          |
|:--------:|:--------:|:----------------------:|:---------------------------:|
|28/08/2019| 1.1 | Criação do documento       |    Lucas Machado |
|29/09/2019| 1.2 | Preenchendo lacunas | Lucas Machado |
|01/09/2019| 1.3 | Preenchendo lacunas | Eduardo Yoshida |
|01/09/2019| 1.4 | Preenchendo lacunas | Lucas Machado |
|16/11/2019| 1.3 | Atualizando documento | Lucas Machado <br>Eduardo Yoshida |
