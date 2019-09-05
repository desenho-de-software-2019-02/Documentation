# Documento de Visão - Master of Puppets
> O projeto consiste em uma solução que visa auxiliar um mestre de uma mesa de Role Playing Game agindo na gerência de uma sessão ou aventura, e de elementos que as envolvem.

#### Table of Contents
[1 - Introdução](#1---Introdução)

[2 - Problema](#2---Problema)

[3 - Features do Produto](#3---Features-do-Produto)

[4 - Restrições](#4---Restrições)

[5 - Riscos](#5---Riscos)

[6 - Stakeholders e Descrição dos Usuários](#6---Stakeholders-e-Descrição-dos-Usuários)

[7 - Membros do Projeto](#7---Membros-do-Projeto)

#### Palavras-chave
> X, Y, Z...

#### Glossário
| Termo | Sinônimo | Descrição |
| ----- | -------- | --------- |
|  RPG  | Role Playing Game | tipo de jogo em que os jogadores assumem papéis de personagens e criam narrativas colaborativamente |
| Mestre | Mestre de Mesa, Mestre de Jogo, Dungeon Master (D&D) | jogador responsável por conduzir o jogo, narrando as situações que acontecem com os personagens de outros jogadores |
| D&D | Dungeons & Dragons | Um RPG de alta fantasia desenvolvido em 1974. Considerado como a origem dos RPG's modernos |
| Mesa | |  A forma original de RPG, às vezes chamada de RPG de mesa (tabletop RPG em inglês), é conduzida através de discussões |
| Sessão | | Cada sessão de RPG pode ser chamada de uma aventura. |
| Campanha | | Uma sucessão de aventuras onde se usam os mesmos personagens mantendo a continuidade dos eventos. |
| NPC's | Non-playable character | |
| Storyline | | |
| PWA | Progressive Web-App | |


## 1 - Introdução
#### 1.1 Propósito do Documento
Esse documento delineia a visão do sistema Master of Puppets.
Os propósitos desse documento são:
* Identificar e acordar os problemas enfrentados pelos usuários/jogadores de RPG's de mesa.
* Coletar e descrever os potenciais anseios de features/ferramentas que os jogadores possam desejar
* Propor soluções aos problemas vigentes
* Identificar restrições à solução proposta
* Identificar stakeholders e tipos de usuários
* Identificar o time de desenvolvimento do software

#### 1.2 Escopo
O escopo do projeto está limitado ao auxilio de sessões de RPG presenciais.

#### 1.2 Referências extras (?)

## 2 - Constatação do Problema
| O problema é: | Afetando | Tendo como impacto |
| ---------- | ----- | ------------------- |
| O mestre de mesa é responsável pela<li>Administração de fichas de<ul><li>Jogadores</li><li>Monstros</li><li>NPC's</li></ul></li><li>A definição e elaboração de quests</li><li>Manteneção da storyline do jogo</li>O que tende à ser muito burocrático e maçante | A fluidez das sessões, e consistência da própria história. | Sessões demasiadamente longas (por conta da ineficácia instrínseca à gerência das mesmas), que torna-as menos prazerosas; além de, dessa forma, atrapalhar no "agendamento" de outras sessões já que há de se reservar muito tempo para que estas ocorram |

#### Uma solução de sucesso deveria prover ao usuário:
* Uma sessão de RPG mais fluída
* Uma sessão de RPG mais consistente


## 3 - Features do Produto
#### 3.1 A possibilidade de manipular fichas de **personagens**, incluindo isto:
1. Perícia
2. Índole
3. Informações básicas
   - Nome
   - História
   - Idade, etc
4. **Classe**
5. **Raça**
6. **Itens**
7. **Skills**
8. Experiência (levels)
9. Atributos
10. HP
11. Equipamentos

#### 3.2 A possibilidade de manipular itens, incluindo isto:
1. Informações básicas
   * Nome
   * Breve descrição
   * Status do item
2. Tipo
3. Preço
4. Peso
5. Efeito

#### 3.3 A possibilidade de manipular skills, incluindo isto:
1. Informações básicas
   * Nome da skill
   * Breve descrição sobre a mesma
2. Classe
3. Efeito
4. Cargas

#### 3.4 A possibilidade de manipular classes, incluindo isto:
1. Informações básicas
   * Nome da classe
   * Descrição
2. Efeito
3. Skills
4. Restrições

#### 3.5 A possibilidade de manipular Usuários, incluindo isto:
1. Nome de Usuário
2. Senha
3. Email
4. Personagens
5. Itens
6. Skills
7. Raças

#### 3.6 A possibilidade de manipular Eventos, incluindo isto:
1. Hora/data
2. Partida
3. Descrição
4. Envolvidos
5. Efeito

#### 3.7 A possibilidade de manipular Raças, incluindo isto:
1. Informações básicas
   * Nome
   * Descrição
2. Efeito
3. Skills
4. Restrições

#### 3.8 A possibilidade de manipular Partidas, incluindo isto:
1. Informações
2. Regras
3. Jogadores
4. Mestre de Mesa
5. Eventos
6. Personagens
7. Estado

## 4 - Restrições
#### 4.1 Restrições de Arquitetura/Desenho
##### 4.1.1 Multiplataformas
O sistema utilizará as linguagens/ferramentas acordadas pela equipe, incluindo:
* Python/Flask
* TypeScript/Angular
* MongoDB

O sistema deve ser multiplataforma e rodar nos navegadores mais comuns: Google Chrome, Mozilla Firefox, Opera, Edge e Safari.

Além disso, deve ser um PWA -- ou seja, se comportar da mesma forma independente de estar sendo utilizado num celular ou num computador.
##### 4.1.2 Features dispostas como Serviços
Onde for possível, o sistema será desenvolvido de forma que as features listadas acima estejam dispostas como serviços.

## 5 - Riscos
Possíveis riscos para uma implementação de sucesso (mas não limitados a):
- Complicações que podem surgir relativas à gerência de uma equipe tão grande (composta por 11 membros)
- Sistema não "amigável" pro usuário
- Exigências que a disciplina porventura possa exigir que confrontem o ~flow natural de desenvolvimento
- Mudanças nos requisitos básicos já previamente definidos

## 6 - Stakeholders e Descrição dos Usuários
#### 6.1 Stakeholders
| Nome | Representa | Papel no Projeto |
| ---- | ---------- | ---------------- |
| Millene | Coordenadora da Disciplina | Validação e Verificação da qualidade do projeto (no que tange a Arquitetura e aplicação de Design Patterns relevantes no projeto) |
| André Filho | Gerência | Ser o maestro que concilia tanto a gerência das tribos como auxiliar nas complicações de integração dos microsserviços que possam surgir |

#### 6.2 Usuários
| Título | Papel | Descrição de utilização |
| ------ | ----- | ----------------------- |
| Aventureiro | Usuário padrão da Partida | Ficará encarregado apenas de Jogar, de fato, o jogo. (isso inclui montar a própria ficha etc) |
| Mestre de Mesa | Coordenador da Partida | Ficará encarregado de coordenar e manter o jogo. |

## 7 - Membros do Projeto
| Membro | Responsabilidades | Area Representada |
| ------ | ---------------- | ----------------- | ----------------- |
| André Bargas | <li>Evoluir e Manutenir o Software/Sistema</li><li>Gerenciar a Tribo Miranha</li>  | Software e Planejamento |
| André de Sousa Costa Filho | <li>Evoluir e Manutenir o Software/Sistema</li><li>Gerenciar os gerentes das Tribos</li> | Software e Planejamento |
| André Eduardo Souza de Oliveira | Evoluir e Manutenir o Software/Software | Software |
| Arthur Rodrigues | Evoluir e Manutenir o Software/Sistema | Software |
| Arthur José Benedito de Oliveira Assis | <li>Evoluir e Manutenir o Software/Sistema</li><li>Gerenciar a Tribo Miranha</li> | Software e Planejamento |
| Eduardo Yoshida | Evoluir e Manutenir o Software/Sistema | Software |
| Guilherme de Lyra | Evoluir e Manutenir o Software/Sistema | Software |
| Gustavo Duarte Moreira | Evoluir e Manutenir o Software/Sistema | Software |
| João Pedro de Aquino Corrêa Martins | Evoluir e Manutenir o Software/Sistema | Software |
| Lucas Machado Martins | Evoluir e Manutenir o Software/Sistema | Software |
| Mateus Nóbrega | Evoluir e Manutenir o Software/Sistema | Software |
