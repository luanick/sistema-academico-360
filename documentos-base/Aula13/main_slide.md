<!-- Convertido de: documentos-base/Aula13/main_slide.pdf -->

<!-- página 1 -->

# Engenharia de Software

### Gestão de Projetos

### Professor da disciplina

### 22/10/2026

<!-- página 2 -->

## O que já sabemos até aqui

- Aula 11: o tempo pela lógica preditiva — rede de atividades, caminho crítico, folga, Gantt;

- Aula 12: o mesmo tempo pela lógica ágil — releases, sprints, capacidade, backlog

priorizado;

- os dois planos supõem que as pessoas certas estarão disponíveis quando a atividade

começar, e não dizem quanto isso custa;

- hoje: quem executa cada parte, quem decide, e quanto custa o plano — última aula de

conteúdo da N2.

Professor da disciplina 2/14

<!-- página 3 -->

## Resumo da aula de hoje

### A Aula 13 fecha a N2 respondendo quem faz, quem

### decide e quanto custa — sobre as mesmas atividades,

### marcos e releases das Aulas 11 e 12.

- Recursos e responsabilidades: alocação, superalocação e nivelamento, fazer ou

contratar, matriz RACI;

- Custos: tipos de custo, estimativas, reservas, linha de base e orçamento.

Professor da disciplina 3/14

<!-- página 4 -->

## Onde isso aparece na prática


- “

PMBOK: na 6 edição, áreas de Recursos e de Custos (processos Estimar custos e

“

Determinar o orçamento); na 7 , domínios de desempenho Equipe e Planejamento;

- ferramentas: MS Project e similares marcam superalocação na planilha de recursos; Jira

e Azure DevOps calculam capacidade por pessoa; o orçamento costuma viver numa

planilha com horas x custo-hora;

- contratos: fornecedores entram com preço fechado ou por hora — cada modalidade

transfere risco de forma diferente;

- para o engenheiro de software: a sua estimativa de horas é a entrada do orçamento:

um erro de 30% nas horas vira um erro de 30% no custo das pessoas.

Professor da disciplina 4/14

<!-- página 5 -->

### Recursos e res-

### ponsabilidades

Quem faz cada parte do

trabalho, e quem decide

quando as pessoas discordam.

<!-- página 6 -->

## Recursos e alocação

Recurso é o que o projeto consome para executar o trabalho: pessoas, materiais, tecnologia.

Tipo Exemplos em projeto de software

Humano desenvolvedores, analistas, designers, gerente, especialistas

Material equipamentos, dispositivos, etiquetas, licenças compradas

Tecnológico servidores, nuvem, ambientes de teste, ferramentas

Alocação

Para cada pessoa: em quais atividades, com que dedicação (%) e em que período. Uma

pessoa a 50% em 24 semanas não equivale a uma pessoa a 100% em 12 — a atividade

depende de quando ela está disponível.

Professor da disciplina 5/14

<!-- página 7 -->

## Superalocação e nivelamento — exemplo

Landing page da Aula 11, mas só existe uma analista para escrever o conteúdo (A) e criar o

layout (B).

dia 1 2 3 4 5 6 7 8 1 2 3 4 5 6 7 8

Plano da Aula 11 Nivelado

A (analista) A (analista)

peralocação

B (analista) B (analista)

s 1—2: 200%

C (dev) C (dev)

D (dev) D (dev)

Leitura

B tinha 1 dia de folga, mas precisa de 2 dias depois de A. Nivelar resolve a

superalocação e alonga o prazo de 6 para 8 dias: o caminho crítico passa a incluir a

disponibilidade da pessoa.

Professor da disciplina 6/14

<!-- página 8 -->

## Fazer ou contratar

Decisão entre executar com a equipe interna ou adquirir de um fornecedor. Critérios: custo,

prazo, competência disponível na equipe, risco e controle sobre o resultado.

Opção para o conflito A/B Prazo Custo de B O que se assume

Fazer: nivelar (analista faz A e 8 dias R$ 640 16 h x R$ 40/h; prazo maior

B)

Contratar: designer externo 6 dias R$ 900 preço fechado; depende de terceiro,

para B menos controle sobre revisões

Decisão

Depende de qual restrição é mais firme. Se a página precisa estar no ar para uma

campanha em 6 dias, pagar R$ 260 a mais é a decisão coerente. Se o prazo é flexível,

nivelar. Nos próximos exemplos, a equipe contratou o designer.

Professor da disciplina 7/14

<!-- página 9 -->

## RACI (Responsável, Aprovador, Consultado, Informado)

R Responsável — executa o trabalho (pode haver mais de um) • A Aprovador — decide em caso de

divergência (exatamente um por entrega) • C Consultado — ouvido antes da decisão • I Informado —

sabe o resultado depois

### Quando ninguém sabe quem decide, quem executa ou

### quem precisa ser avisado, o projeto trava ou atrasa —

### mesmo com um cronograma correto.

- Trabalho sem dono: a entrega existe no plano, mas na hora ninguém se sente

responsável por fazê-la;

- Decisão sem dono, ou com dois donos: falta alguém que decida, ou duas pessoas

acham que a palavra final é delas — os dois casos travam o trabalho;

- Comunicação mal calibrada: gente consultada demais perde tempo; gente informada de

menos é pega de surpresa.

Professor da disciplina 8/14

<!-- página 10 -->

## Matriz RACI — exemplo

Entrega Cliente Gerente Analista Designer Dev

(contra-

tado)

A. Conteúdo A C R C I

B. Layout A C C R I

C. Página montada I A C C R

D. Página publicada I A I I R

Regra e erro comum

As linhas são as entregas do plano, as colunas são pessoas. Erro comum: pôr cliente e

gerente como A no layout — quando discordarem, ninguém decide; ou alguém I em

tudo, sem motivo.

Professor da disciplina 9/14

<!-- página 11 -->

### E quanto custa?

O mesmo plano, agora em reais

— do custo estimado ao orça-

mento que a equipe vai defender.

<!-- página 12 -->

## Tipos de custo

Tipo Definição Exemplo (landing page)

Direto atribuível só a este projeto horas da analista e do dev; designer

contratado

Indireto compartilhado com outros projetos, entra por aluguel e energia do escritório

rateio

Fixo não muda com a quantidade de trabalho domínio e hospedagem (R$

300/ano); designer a preço fechado

Variável cresce com o volume de trabalho horas da equipe interna: cada dia a

mais custa mais

As duas classificações são independentes: as horas do dev são um custo direto e variável; a

hospedagem, direto e fixo.

Professor da disciplina 10/14

<!-- página 13 -->

## Estimativa de custo

Técnica Como funciona Exemplo

Analogia usa o custo real de um projeto pare- “a última landing page custou R$ 4.500” —

cido, ajustado rápida, pouco precisa

Paramétrica quantidade x custo unitário 16 h de dev x R$ 45/h = R$ 720

Bottom-up estima cada atividade ou pacote e soma de A, B, C, D, gestão e materiais

soma (próximo frame)

PERT (O + 4M + P)/6 sobre o custo O = R$ 4.000, M = R$ 4.400, P = R$

5.500 ⇒ R$ 4.517

Analogia, paramétrica e PERT são as mesmas da Aula 8, agora em reais em vez de horas. Na

prática se combinam: a analogia dá a ordem de grandeza no início; o bottom-up, com custos

paramétricos em cada linha, dá o orçamento que a equipe defende.

Professor da disciplina 11/14

<!-- página 14 -->

## Do custo estimado ao orçamento — exemplo

Item R$

Contingência

A. Conteúdo: analista, 24 h x 40 960

B. Layout: designer, preço fechado 900 Vem de um risco identificado:

C. Montar: dev, 16 h x 45 720 rodada extra de layout (R$ 300,

D. Publicar: dev, 8 h x 45 360

prevista no contrato) + 1 dia de

Gestão: gerente 25% em 6 dias, 12 h x 80 960

dev para remontar (R$ 360).

Domínio, hospedagem, banco de imagens 500

Custo estimado 4.400

Reserva gerencial

+ Contingência (rodada extra de layout) 660

Linha de base de custos 5.060 Para imprevistos não

+ Reserva gerencial (5%) 253

identificados. Fica com a

Orçamento 5.313 organização: o gerente só usa

com autorização.

Professor da disciplina 12/14

<!-- página 15 -->

### Mãos à obra!

Quem faz, quem decide e

quanto custa — agora apli-

cado ao projeto de cada equipe.

<!-- página 16 -->

## N2-CP03: Relatório da Unidade 2

- Fazer o relatório final da N2 — entrega até terça-feira, 23h59.

- Montar o slide para a defesa, na próxima aula.

Instruções completas

Como montar o relatório e o slide: Atividade/main_atividade.pdf.

Professor da disciplina 13/14

<!-- página 17 -->

## Próximo episódio

29/10 — Defesa de Projeto N2.

- Até 8h40: organização das equipes para a defesa.

- 8h40 às 11h: defesa — mesma ordem de sempre dos grupos.

Professor da disciplina 14/14
