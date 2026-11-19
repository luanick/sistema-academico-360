<!-- Convertido de: documentos-base/Aula11/main_slide.pdf -->

<!-- página 1 -->

# Engenharia de Software

### Gestão de Projetos

### Professor da disciplina

### 08/10/2026

<!-- página 2 -->

## O que já sabemos até aqui

▶

a EAP/backlog (Aula 7) decompôs o escopo em pacotes de trabalho/itens de backlog;

▶

as estimativas preliminares (Aula 8) deram esforço e duração a cada pacote;

▶

falta sequenciar esses pacotes no tempo — é o que a aula de hoje resolve.

Professor da disciplina 2/14

<!-- página 3 -->

## Conceitos teóricos da aula

Conceito Definição

Atividade Menor unidade de trabalho com início, fim e duração, derivada

de um pacote de trabalho/item de backlog

Dependência Relação de precedência entre duas atividades (tipos: fim-início,

início-início, fim-fim, início-fim)

Marco Ponto no cronograma sem duração que sinaliza um evento sig-

nificativo

Rede de atividades Representação das atividades conectadas pelas suas dependên-

cias

Caminho crítico / folga Caminho de maior duração na rede (define o prazo mínimo);

folga é a margem de atraso tolerável das demais atividades

Cronograma de Gantt Representação em barras das atividades ao longo do tempo

Professor da disciplina 3/14

<!-- página 4 -->

## Onde isso aparece na prática

▶

é a área de Gerenciamento do Cronograma do PMBOK;

▶

vira artefato real: cronograma no MS Project, roadmap no Jira/Trello/Azure DevOps,

Gantt em relatório de status para cliente ou patrocinador;

▶

para o engenheiro de software: é a base para prometer prazo de entrega, negociar escopo

quando o prazo aperta, e enxergar com antecedência onde um atraso vira risco para o

projeto inteiro.

Professor da disciplina 4/14

<!-- página 5 -->

## Atividade vs. pacote de trabalho

Pacote de trabalho / item de backlog Atividade

▶ ▶

unidade de escopo; unidade de trabalho no tempo;

▶ ▶

responde “o que precisa ser entregue?”. responde “quando acontece e por

quanto tempo?”.

Exemplo

“Tela de login” é pacote de trabalho. “Codificar a tela de login — 2 dias” é atividade.

Professor da disciplina 5/14

<!-- página 6 -->

## Dependências

Conceito Definição Exemplo

Predecessora Atividade que precisa acontecer “Codificar” é predecessora de “Testar”

antes de outra

Sucessora Atividade que depende da conclu- “Testar” é sucessora de “Codificar”

são de outra

Fim-início A sucessora só começa quando a “Testar” só pode começar depois que “Co-

predecessora termina (a mais codificar” terminar

mum na prática)

Início-início As duas atividades podem começar “Documentar a implementação” só pode

juntas começar depois que “Codificar” começar

Fim-fim As duas atividades terminam jun- “Validar os dados” só pode terminar de-

tas pois que “Migrar os dados” terminar

Início-fim A sucessora só termina quando a “Operar o servidor antigo” só pode termi-

predecessora começa (raro) nar depois que o “Novo servidor” começar

a operar

Professor da disciplina 6/14

<!-- página 7 -->

## Marco

Ponto no cronograma sem duração que sinaliza um evento significativo — não consome tempo

nem recursos.

Exemplo

“Escopo aprovado”, “Piloto validado”, “Ambiente de produção liberado” — marcos típicos

de projeto de software.

Professor da disciplina 7/14

<!-- página 8 -->

## Rede de atividades

1. listar atividades com suas durações estimadas;

2. identificar predecessoras de cada atividade;

3. desenhar a rede (atividades conectadas por dependências).

Exemplo

Lançamento de uma landing page: A e B começam juntas; C só começa quando as

duas terminarem.

A. Escrever

conteúdo — 3d

Conteúdo C. Montar D. Publicar

+ layout

OK página — 2d — 1d

B. Criar

layout — 2d

Professor da disciplina 8/14

<!-- página 9 -->

## Caminho crítico e folga

1. somar, para cada caminho do início ao fim, as durações das atividades;

2. o caminho crítico é o caminho mais longo — define a duração mínima do projeto;

3. atividades fora do caminho crítico têm folga: a diferença entre a duração do caminho crítico e a

do caminho que passa por elas;

4. atividades no caminho crítico têm folga zero.

Mesma rede da landing page, agora com as durações somadas por rota:

A. Escrever

conteúdo — 3d

Conteúdo C. Montar D. Publicar

+ layout

OK página — 2d — 1d

B. Criar

layout — 2d

Leitura

Rota A-M-C-D: 3+2+1 = 6 dias (em vermelho: caminho crítico). Rota B-M-C-D:

2+2+1 = 5 dias — a atividade B tem 1 dia de folga.

Professor da disciplina 9/14

<!-- página 10 -->

## Cronograma de Gantt — definição

▶

cada atividade vira uma barra horizontal, posicionada pelas datas já calculadas na rede;

▶

marcos viram pontos (sem largura) no mesmo eixo;

▶

caminho crítico mantém a mesma cor de destaque usada na rede;

▶

atividades com folga mostram, depois da barra, até onde poderiam se estender sem

atrasar o projeto.

Professor da disciplina 10/14

<!-- página 11 -->

## Cronograma de Gantt — exemplo

0 1 2 3 4 5 6

|  | A |  |
| --- | --- | --- |
|  | B |  |

marco

|  | C |
| --- | --- |

D

Leitura

Barras vermelhas (A, C, D) = caminho crítico. Barra de B termina no dia 2, com

extensão pontilhada até o dia 3 — a folga de 1 dia calculada na rede.

Professor da disciplina 11/14

<!-- página 12 -->



<!-- página 13 -->

## N2-CP01: cronograma em papel craft

### Em grupo e em papel craft: rede de atividades, caminho

### crítico, folgas e Gantt do cronograma real do projeto de

### vocês.

•

Em equipe, construído em sala instruções em

Atividade/main_atividade.pdf

•

Individual, em ferramenta digital, até 14/10 (véspera da Aula 12) instruções em

Atividade/main_atividade_individual.pdf

Professor da disciplina 13/14

<!-- página 14 -->

## Próximo episódio

### Se parte do projeto é incerta demais para um cronograma

### fixo, como planejamos o tempo sem fingir uma precisão

### que não existe?

Planejamento ágil/incremental: releases, sprints, capacidade e velocidade.

Professor da disciplina 14/14
