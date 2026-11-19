<!-- Convertido de: documentos-base/Aula12/main_atividade.pdf -->

<!-- página 1 -->

### N2-CP02 — Releases, sprints e incrementos

Gestão de Projetos | Aula 12 — Planejamento ágil e incremental Professor da disciplina

### Como funciona esta atividade

Este guia é autoinstrutivo: a equipe lê e trabalha sozinha, sem exposição teórica adicional do professor. Ele tem três partes:

1. Leitura (Seções 1 a 4) — os conceitos de hoje, com exemplos. Leiam antes de começar

a replanejar.

2. Replanejamento (Seção 5) — partam da mesma premissa que usaram para montar

o cronograma da Aula 11 (lista de atividades, durações, dependências e marcos do projeto de vocês). Desta vez, sigam o caminho ágil em vez do preditivo, construindo em slides, numa ferramenta digital livre (PowerPoint, Google Slides, Canva etc.), produzindo os 10 pontos da Seção 5.

3. Apresentação (Seção 6) — cada equipe apresenta os slides para a turma. A apre-

sentação é a evidência da atividade e gera a nota do checkpoint N2-CP02 (aprovado/não aprovado — critérios na Seção 7).

O que vamos entregar primeiro, em que ciclos, e por que essa é a ordem certa para o nosso projeto?

### 1. Antes de começar: retomem a premissa do projeto

Recuperem a mesma base que a equipe usou na Aula 11 para montar a rede de atividades, o caminho crítico e o Gantt: lista de atividades, durações, dependências e marcos do projeto de vocês. O plano de releases de hoje parte dessa mesma base, mas segue o caminho ágil em vez do preditivo — organiza o mesmo trabalho em ciclos curtos, revisados com frequência, em vez de um escopo fixo do início ao fim.

Professor da disciplina 1

<!-- página 2 -->

### 2. Leitura — conceitos de hoje

Conceito Definição

Planejamento ágil Planejamento em ciclos curtos, com escopo revisado com frequência — não é ausência de plano

Release Entrega maior, composta de vários incrementos, com um objetivo de valor coeso

Sprint / iteração Ciclo curto de trabalho, duração fixa (ex.: 2 semanas), ao final do qual há uma entrega

Incremento Parte funcional e utilizável do produto, entregue ao final de um ciclo

Capacidade Quanto trabalho a equipe estima conseguir realizar em um ciclo, dada a disponibilidade real

Velocidade Quanto trabalho a equipe efetivamente entregou nos últimos ci- clos — métrica histórica, só existe depois de ciclos executados

Priorização de backlog Critério explícito para decidir o que entra primeiro: valor x esforço, ou MoSCoW (Must/Should/Could/Won’t have)

Onde isso aparece na prática: Scrum é o framework mais citado para organizar esses ciclos (papéis, eventos, artefatos) — hoje usamos só o vocabulário, não o framework completo; Kanban é uma variação por fluxo contínuo, sem ciclos fixos. Em ferramentas reais (Jira, Trello, Azure DevOps), isso vira backlog priorizado, sprints com datas e indicadores como burndown/burnup. Para o engenheiro de software, é o que permite prometer valor em sema- nas, não em meses, e reduzir o risco de construir a coisa errada quando o cliente ainda não sabe exatamente o que quer. Planejamento ágil vs. cronograma preditivo (Aula 11): no cronograma preditivo, o escopo é o compromisso fixo e o prazo se calcula a partir dele. No planejamento ágil, a capacidade e o ritmo dos ciclos são o compromisso mais estável, e o escopo de cada ciclo se ajusta. Mesmo assim, o plano ágil ainda tem marcos (fim de cada release) e noção de sequência — o que muda é que o conteúdo de cada ciclo pode mudar, não necessariamente o ritmo.

### 3. Exemplo guiado — transformando uma rede preditiva

### em releases

Retomem o exemplo da landing page da Aula 11: A (escrever conteúdo, 3 dias) e B (criar layout, 2 dias) começam juntas; um marco confirma as duas prontas; C (montar página, 2 dias) e D (publicar, 1 dia) seguem em sequência. O caminho crítico era A-M-C-D (6 dias); B tinha 1 dia de folga.

Professor da disciplina 2

<!-- página 3 -->

Release 1 Release 2

A. Conteúdo 3d Conteúdo C. Montar D. Publicar +layout 2d 1d OK B. Layout 2d

O caminho crítico e os marcos não mudam — o que o replanejamento ágil faz é agrupar as atividades em releases com objetivo de valor próprio: Release 1 entrega "conteúdo e layout prontos"(fim do marco), Release 2 entrega "página publicada". Usem a mesma lógica sobre o projeto de vocês: organizem em slides onde cada release começa e termina, usando as mesmas atividades, dependências e marcos que vocês já tinham mapeado na Aula 11.

### 4. Priorização aplicada — exemplo

Item de backlog Valor Esforço MoSCoW Decisão “ Protótipo de captura de dados Alto Baixo Must have Entra na 1 release “ Modo offline Alto Médio Must have Entra na 1 release

Integração completa com o Alto Alto Should have Só após offline validado ERP em campo

Dashboard de analytics avan- Baixo (por Alto Won’t have Fora desta versão çado ora)

O critério não foi “o que é mais fácil” — foi valor entregue mais cedo (validar a solução em campo) e redução de risco (não investir pesado na integração com o ERP antes de validar o essencial). Justificativa por conveniência da equipe não é aceita como critério de priorização.

### 5. Replanejamento — o que a equipe precisa produzir

A partir da mesma premissa da Aula 11 (atividades, durações, dependências e marcos do projeto de vocês), construam em slides e deixem claro:

1. visão de releases ou incrementos planejados, sobrepostos aos marcos/caminho crítico já

calculados;

2. objetivo de valor de cada release (o que ela representa, não apenas tarefas);

3. itens de backlog incluídos em cada release/sprint;

4. prioridades e critério de seleção usado (valor x esforço ou MoSCoW), com justificativa

escrita;

5. duração das iterações escolhida, se fizer sentido para o projeto;

Professor da disciplina 3

<!-- página 4 -->

6. capacidade estimada da equipe por ciclo;

7. dependências entre itens de backlog;

8. validações previstas — como e quando o cliente/usuário valida cada entrega;

9. relação explícita com o cronograma da Aula 11 — o que permanece (marcos, caminho

crítico) e o que muda (conteúdo de cada ciclo);

10. alterações na decomposição inicial (Aula 7), se houve.

Dica: salvem o arquivo de slides conforme avançam — ele é a evidência da atividade, junto com a apresentação.

### 6. Apresentação

Cada equipe tem até 10 minutos para apresentar os slides construídos, cobrindo, na ordem que preferir, os 10 pontos da Seção 5. Pelo menos dois integrantes devem falar. Ao final, a equipe responde a uma pergunta da turma ou do professor.

### 7. Critérios de aprovação (nota binária)

A equipe é aprovada no N2-CP02 se, na apresentação, ficar claro todos os itens abaixo:

□ o projeto foi replanejado visivelmente em releases/sprints, partindo das mesmas ativi- dades, dependências e marcos usados na Aula 11; □ há backlog priorizado com critério explícito (valor x esforço ou MoSCoW) — não por conveniência da equipe; □ capacidade estimada aparece como estimativa, não é confundida com velocidade histó- rica; □ há relação explícita entre o plano de releases e o cronograma da Aula 11 (o que muda, o que permanece); □ pelo menos dois integrantes participam da apresentação e a equipe responde com segu- rança à pergunta final.

Se faltar algum item essencial, a equipe fica com o checkpoint pendente e recebe um prazo curto (definido em sala) para complementar e reapresentar.

Professor da disciplina 4
