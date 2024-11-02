# Iniciação

> A fase de iniciação, em gerência de projetos, é o estágio que estabelece as bases para o sucesso do empreendimento. 
> Durante essa etapa, os objetivos definidos, identificando-se suas metas, escopo, partes interessadas (*stakeholders*) e restrições. 
> É o momento em que a viabilidade do projeto é avaliada, analisando-se recursos necessários, riscos potenciais e benefícios esperados.
> Nesta etapa é elaborado o Termo de Abertura do Projeto (TAP).
> Essa fase serve como um alicerce estratégico, proporcionando uma compreensão abrangente do que o projeto busca alcançar e delineando as diretrizes que orientarão as etapas subsequentes. 
> O sucesso na fase de iniciação contribui significativamente para a eficácia do gerenciamento de projetos como um todo.

# Estrutura do Documento

- [Fase de Iniciação](#iniciação)
- [Introdução](#introdução)
  - [Problema](#problema)
  - [Objetivos](#objetivos)
  - [Justificativa](#justificativa)
  - [Critérios de Sucessos](#critérios-de-sucesso)
- [Partes Interessadas](#partes-interessadas)
  - [Identificação das Partes Interessadas](#identificação-das-partes-interessadas)
  - [Avaliação das Partes Interessadas](#avaliação-das-partes-interessadas)
- [Termo de Abertura do Projeto](#termo-de-abertura-do-projeto)
  - [Estimativa de Custo](#estimativa-de-custo)
  - [Estimativa de Prazo](#estimativa-de-prazo)
  - [Escopo Preliminar e Premissas](#escopo-preliminar-e-premissas)
    - [Requisitos Funcionais](#requisitos-funcionais)
    - [Requisitos Não Funcionais](#requisitos-não-funcionais)
    - [Restrições](#restrições)
    - [Contra-Escopo](#contra-escopo)
    - [Condições para início do Projeto](#condições-para-início-do-projeto)
- [Metodologia](#metodologia)
  - [Divisão de Papéis](#divisão-de-papéis)
  - [Ferramentas](#ferramentas)

# Introdução

```diff
+ Tarefa 01:
+ Tema do projeto e lista de Stakeholders
```

## Problema

Em muitas residências onde pessoas dividem o mesmo espaço, como apartamentos de estudantes ou casas de famílias, a divisão de tarefas domésticas pode se tornar um desafio significativo. A falta de comunicação clara e de coordenação na realização de tarefas pode levar a frustrações, acúmulo de atividades, e até mesmo a conflitos entre os moradores.

Muitos lares enfrentam dificuldades em manter uma rotina doméstica organizada, onde as responsabilidades de cada pessoa são claras e seguidas de maneira eficiente. Sem uma ferramenta adequada, a gestão dessas tarefas depende de conversas esporádicas ou de lembretes informais, que nem sempre são suficientes para garantir que todas as obrigações sejam cumpridas no prazo. Isso resulta em ambientes desorganizados e, frequentemente, em tensões entre os moradores.

## Objetivos

Objetivo do projeto é a realização de um software de gerenciamneto de tarefas domésticas em grupo e que auxilie os usuários no controle de recursos, pessoas e das tarefas, garantindo efetividade da divisão, das execuções, do acompanhamento das tarefas e deveres domésticos sem sobrecarregar e fazendo com que a falta de tempo não seja mais um problema para dividir e realizar as tarefas.

## Justificativa

A escolha desse tema se dá pela dificuldade que muitos grupos domésticos, sejam família ou amigos de um república, enfrentam ao dividir e executar as tarefas domésticas. Isso ocorre devido à falta de tempo, desorganização, sobrecarga de tarefas diárias, esquecimento e divisão de tarefas pouco eficiente.

Com isso, a nossa solução se baseia em alguns benefícios que justificam a incialização do projeto de software, como:
- Divisão de tarefas rápida, eficiente e sem sobrecarregar o usuário.
- Maior controle nas tarefas a serem executadas e em execução.
- Desacúmulo de tarefas diárias e distribuição justa entre os grupos.

## Critérios de Sucesso

1. Desenvolvimento do Projeto de Maneira Efetiva e com Entregas no Prazo e Satisfação do Cliente e da Equipe.
2. Desenvolver uma aplicação que o Design seja 100% focado na experiência do Usuário.
3. Ter um ótimo trabalho em equipe com sucesso na realização de todo o processo do Projeto.
4. Maior Rentabilidade para a Empresa.
5. Ferramenta Estável (Menor Taxa de Erros).
6. Sistema completo que auxilie na organização das tarefas domésticas em grupo dos usuários.
7. Participar ativamente no desenvolvimento do projeto na área de Engenharia e Arquitetura de Software.

# Partes Interessadas

## Identificação das Partes Interessadas

| Nome                                 | Posição / Cargo            | Papel no Projeto                 | E-mail                         | Telefone    |
|--------------------------------------|----------------------------|----------------------------------|--------------------------------|-------------|
| Pedro Henrique Cunha Vieira          | Gerente do Projeto         | Gerente de Projeto               | pedro.vieira@pucminas.br       | 31991239717 |
| Caio Vitor Souza Fernandes           | Gerente de Qualidade       | UX Designer                      | caio.fernandes@pucminas.br     | 31991239711 |
| João Gustavo Medeiros Pontes         | Gerente de DevOps          | Desenvolvedor Back-end           | joao.pontes@pucminas.br        | 31991239712 |
| Sávio Luis Pontes Martuchelli        | Gerente Financeiro         | Analista de finanças             | savio.martuchelli@pucminas.br  | 31991239713 |
| Victor Magalhães de Souza            | Gerente de Desenvolvimento | Desenvolvedor Front-End          | victor.souza@pucminas.br       | 31991239714 |
| Lionel Ronaldo Arantes do Nascimento | CEO                        | Cliente                          | ronaldo.arantes@barsemlona.com | 31924305123 |
| Simone Andrade dos Santos            | Arquiteta de Soluções      | Parceiro de implatanção em nuvem | simone.santos@parisgold.com    | 48912658294 |

## Avaliação das Partes Interessadas

| Nome                                 | Expectativas no projeto                                                                                   | Influência | Importância         | Apoio    | Observações                                          |
|--------------------------------------|-----------------------------------------------------------------------------------------------------------|------------|---------------------|----------|------------------------------------------------------|
| Pedro Henrique Cunha Vieira          | Desenvolvimento do Projeto de Maneira Efetiva e com Entregas no Prazo e Satisfação do Cliente e da Equipe | Alta       | Alta                | Apoiador | Gerente de Projeto                                   |
| Caio Vitor Souza Fernandes           | Desenvolver uma aplicação que o Design seja 100% focado na experiência do Usuário                         | Alta       | Média               | Apoiador | Gerente de Qualidade - UX Designer                   |
| João Gustavo Medeiros Pontes         | Ter um ótimo trabalho em equipe com sucesso na realização de todo o processo do Projeto                   | Alta       | Média               | Apoiador | Gerente de DevOps - Desenvolvedor Back-end           |
| Sávio Luis Pontes Martuchelli        | Maior Rentabilidade para a Empresa                                                                        | Alta       | Média               | Apoiador | Gerente Financeiro - Analista de finanças            |
| Victor Magalhães de Souza            | Ferramanenta Estável(Menor Taxa de Erros), com Front-End                                                  | Alta       | Média               | Apoiador | Gerente de Desenvolvimento - Desenvolvedor Front-End |
| Lionel Ronaldo Arantes do Nascimento | Sistema completo que auxilie na organização domicilial dos usuários                                       | Alta       | Alta                | Apoiador | Cliente                                              |
| Simone Andrade dos Santos            | Participar ativamente no desenvolvimento do projeto na área de Arquitetura de Solução                     | Alta       | Média               | Apoiador | Parceiro de implatanção em nuvem                     |

```diff
+ Tarefa 01
+ Fim da seção a ser atualizada.
```


-----
```diff
+ Tarefa 02
+ Termo de Abertura do Projeto
```

# Termo de Abertura do Projeto

> O Termo de Abertura do Projeto (TAP) representa o ponto de partida oficial para o empreendimento. 
> Ele sintetiza de maneira clara e concisa os objetivos, escopo, partes interessadas envolvidas, entregas esperadas, cronograma preliminar e recursos necessários para a execução bem-sucedida do projeto. 
> O TAP funciona como um contrato inicial entre a equipe do projeto e as partes interessadas, estabelecendo as bases para uma compreensão compartilhada dos propósitos e limites do projeto. 
> Ao delinear esses elementos de forma detalhada, o Termo de Abertura do Projeto (TAP) fornece uma direção sólida para orientar as atividades subsequentes, facilitando a gestão eficaz do projeto desde o início até o encerramento. 
> Essa documentação garante a clareza, alinhamento e comprometimento de todos os envolvidos, contribuindo assim para o sucesso do projeto.

## Estimativa de Custo

| Item de custo                       | Qtd. horas | Valor / hora | Valor total |
|-------------------------------------|------------|--------------|-------------|
| 4.1 Recursos Humanos (especifique): | 520        | 262,97       | 136.744,40  |
| 4.2 Hardware (especifique):         | -          | -            | -           |
| 4.3 Rede e serviços de hospedagem:  | 2280       | 2,78         | 6.338,40    |
| 4.4 Software de terceiros:          | -          | -            | -           |
| 4.5 Serviços e treinamento:         | -          | -            | -           |
| 4.6 Total Geral:                    | 2800       | 265,75       | 143.082,80  |

## Estimativa de Prazo

* Prazo previsto (em horas): 520 horas
* Data de início: 29/08/2024
* Data de término: 01/12/2024

## Escopo Preliminar e Premissas

### O que será feito (escopo do projeto)
- Desenvolvimento de aplicação de gerenciamento de tarefas domésticas para repúblicas, grupos familiares, cônjuges e colegas de quarto.

### O que não será feito no projeto (contra-escopo)
- A aplicação não se refere a gerenciamento de tarefas individuais ou agendas.

### Condições para iniciar o projeto)
- Será necessário contratar um provedor de nuvem para hospedar a aplicação back-end
- Será necessário utilizar um banco de dados relacional altamente disponível
- É necessário um orçamento inicial para mobilização da equipe e do maquinário
- Comprar licença de venda nas lojas de aplicações móveis da Google e da Apple
- Será necessária configuração de repositórios para as aplicações front e back-end

## Declaração de Escopo

### Requisitos Funcionais

A tabela a seguir apresenta os requisitos funcionais do projeto. 

| ID     | Descrição do Requisito                         | Prioridade |
|--------|------------------------------------------------|------------|
| RF-001 | Cadastrar tarefas                              | ALTA       |
| RF-002 | Excluir tarefas                                | MÉDIA      |
| RF-003 | Alterar tarefas                                | MÉDIA      |
| RF-004 | Visualizar tarefas                             | BAIXA      |
| RF-005 | Cadastrar casas                                | ALTA       |
| RF-006 | Excluir casas                                  | MÉDIA      |
| RF-007 | Alterar casas                                  | MÉDIA      |
| RF-008 | Visualizar casas                               | BAIXA      |
| RF-009 | Cadastrar usuários                             | ALTA       |
| RF-010 | Excluir usuários                               | MÉDIA      |
| RF-011 | Alterar usuários                               | MÉDIA      |
| RF-012 | Visualizar usuários                            | BAIXA      |
| RF-013 | Colocar prioridade na tarefa                   | ALTA       |
| RF-014 | Compartilhar link da casa para outros usuários | ALTA       |
| RF-015 | Escolher tarefa a executar                     | ALTA       |
| RF-016 | Alocar usuário para tarefa                     | ALTA       |

### Requisitos Não Funcionais

A tabela a seguir apresenta os requisitos não funcionais do projeto. 

|ID     | Descrição do Requisito                                                                                                 |Prioridade |
|-------|------------------------------------------------------------------------------------------------------------------------|-----------|
|RNF-001| O sistema deve ser responsivo para rodar em um dispositivos móvel                                                      | MÉDIA     | 
|RNF-002| Deve processar requisições do usuário em no máximo 3s                                                                  | BAIXA     |
|RNF-003| O sistema deve ser desenvolvido utilizando Flutter como tecnologia no front-end                                        | ALTA      | 
|RNF-004| O sistema deve possuir simplicidade suficiente para que usuário inexperientes em tecnologia consigam usá-lo            | ALTA      | 
|RNF-005| O sistema deve possuir uma arquitetura cliente-servidor hospedada na internet                                          | BAIXA     | 

### Restrições

A tabela a seguir apresenta as restrições do projeto. 

| ID     | Descrição do Requisito                                                             | Prioridade |
|--------|------------------------------------------------------------------------------------|------------|
| RE-001 | Permitir que o usuário cadastre tarefas                                            | ALTA       |
| RE-002 | Permitir que o usuário delete tarefas                                              | MÉDIA      |
| RE-003 | Permitir que o usuário altere tarefas                                              | MÉDIA      |
| RE-004 | Permitir que o usuário visualize tarefas                                           | BAIXA      |
| RE-005 | Permitir que o usuário veja progessos por tipo de tarefas                          | MÉDIA      |
| RE-006 | Permitir que o usuário visualize tarefas atribüidas                                | ALTA       |
| RE-007 | Permitir que o usuário visualize tarefas em andamento                              | ALTA       |
| RE-008 | Permitir que o usuário visualize tarefas realizadas                                | ALTA       |
| RE-009 | Permitir que o usuário visualize tarefas removidas                                 | BAIXA      |
| RE-010 | Permitir que o usuário visualize porcentagem das tarefas do grupo foram realizadas | BAIXA      |
| RE-011 | Permitir que o usuário defina prioridade e peso da tarefa                          | ALTA       |
| RE-011 | Permitir que o usuário compartilhe o link da casa                                  | ALTA       |

##### Outras restrições do projeto
- O projeto deve ser concluído até o fim de 2024
- Para o projeto será disponibilizada uma equipe de, no máximo, 6 pessoas
- O projeto não pode consumir mais que R$ 150.000,00
- O front-end precisará ser desenvolvido em Flutter

### Contra-Escopo

|ID    | Descrição do Contra-Escopo                  |
|------|---------------------------------------------|
|CE-001| Gerencimaneto de tarefas individuais        |
|CE-002| Aplicação de agenda pessoal                 |
|CE-003| Gerenciador de tempo de execução de tarefas |
|CE-004| Automatização das tarefas                   |
|CE-005| Aplicação de anotações                      |

### Condições para início do Projeto

A tabela a seguir, apresente as condições para que o projeto seja iniciado.

| ID     | Descrição de Condições para Início do Projeto    |
|--------|--------------------------------------------------|
| CI-001 | Assinatura de contrato de prestação de serviços. |
| CI-002 | Apresentação de garantias definidas no contrato. |
| CI-003 | Requisitos funcionais                            |
| CI-004 | Requisitos não-funcionais                        |
| CI-005 | Personas                                         |
| CI-006 | Definição do problema                            |
| CI-007 | Mapa de empatia                                  |
| CI-008 | Brainstorming                                    |
| CI-009 | Brainwriting                                     |
| CI-010 | Proposta de valor                                |
| CI-011 | Formação de equipe                               |
| CI-012 | Ambiente de desenvolvimento                      |
| CI-013 | Alinhamento com cliente                          |

### Marcos agendados e entregas
1. Identificação da comunidade e da demanda: Brainstorm de ideias; Levantamento das personas; Matriz CSD; Mapa de empatia; Levantamento de requisitos; Protótipo de baixa fidelidade
2. Finalização da UX/UI: Protótipos de alta fidelidade; Telas implementadas em Flutter
3. Implementação das funcionalidades: Navegação entre as telas; Implementação de funcionalidades que não exigem permanência de dados; Modelagem e implementação do banco de dados
4. Finalização do app: Implementação do Back-end com funcionalidades que dependem de permanência dos dados; Testes alfa e beta com os usuários
5. Finalização do projeto: Lançamento do app construído; Levantamento dos desafios encontrados

```diff
+ Tarefa 02
+ Fim da seção a ser atualizada.
```

-----
```diff
+ Tarefa 03:
+ Metodologia do Projeto
```

# Metodologia

- Decisão de Metodologia: Utilização da metodologia ágil Kanban através da utilização da aplicação GitHub Projects.
- Agendamento de Reuniões: Agendamento de Reuniões semanais com duração de 30 minutos a 1 hora.
- Divisão de Tarefas para Desenvolvimento:
  - Pedro Henrique (Gerente de Projeto)
  - Caio Vitor (UX Designer)
  - João Gustavo (Desenvolvedor BackEnd)
  - Victor Magalhães (Desenvolvedor FrontEnd)
  - Sávio Luis (Analista de Finanças)
- Estimativas de Custos:
  - Custos nas Áreas de Recursos Humanos
  - Hardwares
  - Redes e Serviços
  - Software de Terceiro
  - Serviços de Treinamento.

## Divisão de Papéis

| Nome                                 | Posição / Cargo            | Papel no Projeto                 |
|--------------------------------------|----------------------------|----------------------------------|
| Pedro Henrique Cunha Vieira          | Gerente do Projeto         | Gerente de Projeto               |
| Caio Vitor Souza Fernandes           | Gerente de Qualidade       | UX Designer                      |
| João Gustavo Medeiros Pontes         | Gerente de DevOps          | Desenvolvedor Back-end           |
| Sávio Luis Pontes Martuchelli        | Gerente Financeiro         | Analista de finanças             |
| Victor Magalhães de Souza            | Gerente de Desenvolvimento | Desenvolvedor Front-End          |
| Lionel Ronaldo Arantes do Nascimento | CEO                        | Cliente                          |
| Simone Andrade dos Santos            | Arquiteta de Soluções      | Parceiro de implatanção em nuvem |

## Ferramentas

| Ambiente                      | Plataforma   | Link de Acesso      | Justificativa                                                     |
|-------------------------------|--------------|---------------------|-------------------------------------------------------------------|
| Quadro Kanban                 | Github       | [https://github.com](https://github.com/orgs/ICEI-PUC-Minas-PCO-SI/projects/67)  | Centralização e organização do projeto no próprio repositório.    |
| Repositório de código         | GitHub       | [https://github.com](https://github.com/CoHabito-Dev/Front)  | Fácil gerenciamento e versionamento                               |
| Protótipo de Baixa Fidelidade | Figma        | [https://figma.com](https://www.figma.com/design/PMHY18FZ2DFzoEmZaoDiQV/CoH%C3%A1bito?node-id=0-1&t=ol0XnXTO2z9MjhrO-1)   | Centralização dos componentes e interface                         |
| Protótipo de Alta Fidelidade  | Figma        | [https://figma.com ](https://www.figma.com/design/CO5nvxVLFkHneTKqT3JdrQ/Untitled?node-id=1-2&t=8I3wmmeimike07Fe-1)  | Centralização dos componentes e interface                         |
| Documentos Textuais           | Google Drive | [Google Drive](https://drive.google.com/drive/folders/1Jz2V39s8iSs3_3gI8w8lAHO1DYeanUkG?usp=sharing) | Ferramenta grátis e em nuvem para todos os integrantes do projeto |
| Elementos Gráficos do Projeto | Google Drive | [Google Drive](https://drive.google.com/drive/folders/1BWYyt4XrZOIscKN7GgamL3Jozix7Un6W?usp=sharing)        | Ferramenta grátis e em nuvem para todos os integrantes do projeto |
| EAP / WBS                     | Draw.io      | Draw.io             | Criação de estrutura analítica graficamente grátis e de fácil usabilidade |
| Cronograma do Projeto         | MS Project   |                     | Ferramenta de altíssima qualidadde para gerenciar projetos e recursos |
| Matriz RACI                   | Google Docs  | [Google Docs](https://drive.google.com/file/d/11M9XY38XE75GcS0rGfoRquVka7aNjX_W/view?usp=sharing)   | Ferramenta grátis e em nuvem para todos os integrantes do projeto |

```diff
+ Tarefa 03:
+ Fim da seção a ser atualizada.
```

----
