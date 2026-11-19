<!-- Convertido de: documentos-base/Aula08/main_slide.pdf -->

<!-- página 1 -->

# Engenharia de Software

### Gestão de Projetos

### Professor da disciplina

### 17/09/2026

<!-- página 2 -->

## Ponte com a Aula 7

A decomposição de hoje ganha uma primeira noção de tamanho — e essa noção fecha a teoria da unidade N1.

Pergunta de transição

Agora que o trabalho está dividido em partes gerenciáveis, quanto esforço, tempo e

recursos cada parte parece exigir?

▶

a Aula 7 decompôs o escopo em EAP, backlog ou estrutura híbrida;

▶

hoje essas unidades recebem uma primeira estimativa preliminar;

▶

esta é a última aula antes da N1 — e é uma aula curta: fecha a teoria e libera as duas

entregas finais da unidade.

Professor da disciplina 2/15

<!-- página 3 -->

## O que vamos ver hoje

Aula curta: cinco paradas, todas fechando a teoria da unidade

▶

quatro dimensões da estimativa — tamanho, esforço, duração e custo;

▶

onde essas dimensões vivem na prática;

▶

incerteza e premissas nas estimativas;

▶

onde premissa e incerteza vivem na prática;

▶

as duas entregas que fecham a N1.

Professor da disciplina 3/15

<!-- página 4 -->

## Resultado esperado da aula

Sair hoje sabendo diferenciar as quatro dimensões da estimativa e reconhecer onde cada uma vive nos

artefatos que a equipe já produz.

▶

diferenciar tamanho, esforço, duração e custo;

▶

reconhecer onde essas dimensões vivem na prática — dentro da EAP/backlog, do

cronograma e do orçamento;

▶

registrar premissas explícitas em cada estimativa, sem fingir certeza;

▶

reconhecer que premissa tem artefato próprio (Registro de Premissas) e que incerteza

grande deixa de ser estimativa e vira risco.

Entregas

▶

lista individual;

▶

Dossiê de equipe;

ficam abertas até 23/09/2026.

Professor da disciplina 4/15

<!-- página 5 -->

### Tamanho não é prazo

<!-- página 6 -->

## Tamanho não é prazo

Duas coisas que parecem do mesmo tamanho nem sempre custam o mesmo tempo — por quê?

Provocação

Peguem dois pacotes de trabalho da Estrutura Analítica do Projeto (EAP) ou do

backlog que a equipe de vocês já tem (Aula 7), com tamanho parecido na aparência.

Um fica pronto em dois dias; o outro leva duas semanas.

O que pode explicar essa diferença, além da quantidade de trabalho em si? Pensem em

pelo menos duas causas antes de eu revelar a resposta.

Professor da disciplina 5/15

<!-- página 7 -->

## Quatro dimensões da estimativa

Dimensão O que mede Exemplo

Tamanho Quanto trabalho existe 1 tela de cadastro

Esforço Quanto trabalho é necessário para 40 horas-pessoa

fazer

Duração Quanto tempo isso leva no calendá- 3 dias (2 pessoas em paralelo)

rio

Custo Quanto isso consome de recursos fi- R$ 3.000

nanceiros

Cenário: as mesmas 40 horas-pessoa podem ser 1 pessoa por 5 dias, ou 2 pessoas por 3 dias — mesmo esforço,

durações diferentes.

Síntese

Tamanho, esforço, duração e custo são relacionados, mas não são a mesma coisa —

confundi-los é uma das causas mais comuns de estimativa errada.

Professor da disciplina 6/15

<!-- página 8 -->

### Onde isso vive na prática?

<!-- página 9 -->

## Onde cada dimensão vive na prática

Nenhuma das quatro tem formulário próprio — cada uma vira um campo concreto dentro de um artefato que

a equipe já produz.

Dimensão Onde vive na prática Exemplo concreto

Tamanho Campo no backlog ou dicionário da “tela de login” = tamanho P (pequena,

EAP perto das outras telas)

Esforço Dicionário da EAP/backlog — alimenta 16h para o pacote “cadastro de pacientes”

cronograma e orçamento

Duração Lista de atividades e cronograma 3 dias úteis p/ “integração financeira”

(Gantt)

Custo Orçamento / linha de base de custos R$ 2.400 no fornecedor do gateway

Síntese

Vocês não vão entregar um “documento de estimativa” — vão adicionar uma coluna

nova na EAP ou no backlog que já têm, preparando o terreno para o cronograma e o

orçamento da N2.

Professor da disciplina 7/15

<!-- página 10 -->

## P/M/G vira número: a luz no fim do túnel

Caminho 1 — Ancoragem em referência (= estimativa análoga)

A equipe compara com um item já concluído e conhecido — “isso é do mesmo tamanho

da tela de login que já fizemos, também é P”.

Caminho 2 — Conversão empírica por velocidade (= estimativa paramétrica)

Ao longo de vários ciclos, a equipe mede quantos pontos completa por sprint — essa

taxa observada, aplicada à quantidade restante, transforma P/M/G em prazo real.

Quando não dá para esperar histórico

Sem velocidade acumulada, usam-se técnicas quantitativas diretas — paramétrica,

análoga ou três pontos (PERT, sigla em inglês para Técnica de Avaliação e Revisão de

Programas) — que já produzem horas, dias ou custo.

Professor da disciplina 8/15

<!-- página 11 -->

## Detalhando PERT

PERT = Program Evaluation and Review Technique — Técnica de Avaliação e Revisão de Programas.

Análoga e paramétrica já eram os Caminhos 1 e 2 — a única novidade de verdade é esta.

Como funciona

Em vez de um número único, a equipe estima três cenários para o mesmo item:

Otimista (O) — se tudo correr bem; Mais provável (M) — o cenário mais realista;

Pessimista (P) — se as coisas derem errado.

Fórmula (média ponderada)

O + 4M + P

E = — o cenário mais provável pesa 4 vezes mais que os dois extremos.

6

Exemplo

O = 2 dias, M = 4 dias, P = 12 dias ⇒ E = (2 + 4×4 + 12) / 6 = 5 dias.

Professor da disciplina 9/15

<!-- página 12 -->

### Incerteza e premissas

<!-- página 13 -->

## O que são incerteza e premissa?

Antes de saber onde registrar, precisamos saber do que estamos falando.

Incerteza

O quanto uma estimativa pode estar errada, pra mais ou pra menos — quanto menos se

sabe sobre a tarefa, maior ela é.

Premissa

Algo que a equipe assume como verdadeiro para poder estimar, mesmo sem

confirmação — se depois for falso, a estimativa muda.

Professor da disciplina 10/15

<!-- página 14 -->

## Onde premissa e incerteza vivem na prática

Premissa tem um endereço formal — incerteza pequena não precisa de documento novo, incerteza grande

muda de nome.

Elemento Onde vive na prática

Premissa Tem artefato formal próprio — o Registro de Premissas — e já apa-

rece dentro do Termo de Abertura que vocês fizeram na Aula 4

Incerteza pequena Vira uma faixa dentro do próprio campo de estimativa (ex.: “3 a 8

dias”), sem documento novo

Incerteza grande Deixa de ser estimativa imprecisa e escala para o Registro de Riscos

Professor da disciplina 11/15

<!-- página 15 -->

## Premissa e faixa, juntas num exemplo

A teoria vira prática quando premissa e faixa aparecem registradas juntas, no mesmo pacote de trabalho.

Pacote: integração com gateway de pagamento

Estimativa: entre 3 e 8 dias (faixa, não número fechado)

Premissa registrada: “assumimos que a documentação do gateway já está pronta e

que não vai precisar de homologação extra”

Por que faixa, e não um número fechado?

Quanto menos a equipe sabe sobre o fornecedor, mais larga a faixa — se a integração já

tivesse sido testada antes, a faixa encolheria (ex.: “4 a 5 dias”).

Professor da disciplina 12/15

<!-- página 16 -->

## Exemplo aplicado — Clínica Conecta (P1)

A integração financeira concentra a maior incerteza porque depende de um ator externo à equipe.

Pacote de trabalho Tam. Esf. Premissa / Incerteza

Cadastro de pacientes P Baixo Campos já conhecidos das planilhas das clíni-

cas — incerteza baixa

Módulo de agendamento G Alto Regras de conflito de horário entre as 3 clíni-

cas ainda não fechadas — incerteza média-alta,

melhor estimar em faixa

Integração financeira G Alto Depende do fornecedor aceitar a integração —

incerteza alta, recomenda-se faixa

Interface acessível (idosos) M Médio Depende de teste com usuários reais — incer-

teza média

Professor da disciplina 13/15

<!-- página 17 -->

### Fechando a N1

<!-- página 18 -->

## Duas entregas, um só prazo

Sem checkpoint em sala hoje — as duas entregas ficam abertas até a véspera da Aula 9.

Lista de revisão individual Dossiê de Iniciação do Projeto

10 exercícios dissertativos (Aulas 6 a 8), O artefato de equipe que fecha a N1,

complementando a lista de 03/09 (Aulas consolidando o que foi produzido desde a

1 a 5) — juntas revisam a Unidade 1 Aula 2 — vale nota em grupo.

inteira. Entregues pelo Teams, cada aluno

entrega o seu — vale nota individual.

Prazo único

Ambas as entregas: até 23/09/2026 (véspera da Aula 9). Comecem hoje, em aula,

com apoio do professor.

Professor da disciplina 14/15

<!-- página 19 -->

## Encaminhamento para a Aula 9

Com o Dossiê já entregue no dia 23, sobra tempo de sobra para ler antes da prova e da defesa.

▶

Aula 9: prova individual pela manhã e seminário com defesa do Dossiê de Iniciação do

Projeto, já entregue no dia 23;

▶

a N1 encerra o ciclo de “compreender, iniciar e definir” — a partir da Aula 10 o foco muda

para “estimar e planejar” (N2);

▶

nenhum artefato da N1 se torna obsoleto — todos serão retomados e expandidos, não

recriados.

Professor da disciplina 15/15
