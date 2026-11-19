<!-- Convertido de: documentos-base/N1_CP03_EQUIPE_2_Sistema_Academico_360 (1).pdf -->

<!-- página 1 -->

### N1-CP03 Abordagem e ciclo de vida

Gestão de Projetos | Aula 3 Ciclos de vida e abordagens Professor da disciplina

### Identificação

| Equipe: | Projeto: |
| --- | --- |
| José, Gustavo, Hugo, Luan, Nicolas, Vinicius | P2 - Sistema Acadêmico 360 |
| Integrantes presentes: | Data / Versão: |
| José, Gustavo, Hugo, Luan, Nicolas, Vinicius | 13/08/2026 v0.1 |

### Prop sito da atividade

Esta atividade transforma a discussão conceitual da aula em uma decisão registrada para o projeto da equipe. A pergunta central é:

Qual abordagem de gerenciamento é mais coerente com o contexto do projeto da equipe?

A equipe deve comparar abordagens preditiva, ágil e híbrida, aplicar critérios de escolha ao projeto, propor um ciclo de vida coerente e registrar consequências práticas para as próximas aulas. A atividade não pede uma resposta bonita ou genérica; pede uma decisão defensável.

### Antes de começar: retome a Aula 2

A escolha da abordagem não começa do zero. Ela deve partir da análise inicial feita na atividade N1-CP01-02. Antes de preencher a matriz desta aula, recuperem as decisões já registradas:

| Elemento da Aula 2 | Resposta da equipe |
| --- | --- |

<!-- página 2 -->

| Decisão preliminar: manter, reduzir, dividir ou reavaliar | manter - O projeto elimina a redundância do sistema legado, unificando os setores acadêmicos e reduzindo trabalhos manuais |
| --- | --- |
| Alternativa considerada mais coerente | Projeto como proposto |
| Benefício principal esperado | União de todos os setores da unidade acadêmica em um mesmo sistema centralizado |
| Restrição, risco ou dependência mais importante | Necessidade de desligar o sistema momentaneamente para transição e migração de dados fora do horário de expediente |
| Dúvida ou premissa que ainda afeta a condução | A estabilidade e a complexidade das interações técnicas com os módulos financeiros e de dados históricos |

### Orientações para a decisão

Use a matriz como instrumento de discussão, nao como uma calculadora automática. Em cada célula, registre se o critério favorece, enfraquece ou exige cuidado naquela abordagem:

+ favorece claramente a abordagem;

- Nao favorece a abordagem;

! exige cuidado, combiná-lo ou adaptá-lo.

Depois do sinal, escreva duas ou três palavras de evidência do caso. Exemplo: + requisitos estáveis, - usuários ausentes, ! fornecedor crítico. Atenção: nao escolha pela coluna com mais sinais. A matriz serve para mostrar quais critérios entram em tensão. A escolha híbrida só faz sentido quando há partes do projeto que pedem controle formal e outras que pedem adaptá-lo, aprendizagem ou entregas parciais.

### 1. Matriz de decisão

| Critério | Preditiva | ágil | Híbrida |
| --- | --- | --- | --- |
| Estabilidade dos requisitos | Requisitos claros de secretaria | Requisitos insertos de interface | Controle no núcleo flexibilidade nas telas |
| Restrições rígidas e variáveis | Prazos de migração de dados | Prazos flexíveis para usuário | Atende prazos fixos e entregas adaptáveis |
| Risco de errar o produto | Falta validação constante | Feedback contínuo de usuários | Validação em incrementos reduz o risco |
| Entregas parciais | Entrega única ao final | Sprints e entregas em partes | Divisao de módulos por etapas |

<!-- página 3 -->

| Dependências externas | Integração financeiras estruturada | Difícil controle de terceiros | Planejamento formal para integrações |
| --- | --- | --- | --- |
| Documentação formal | Exigência de conformidade legal | Foco em software rodando | Documentação focada em dados e normas |
| Participação dos usuários | Usuários distantes da especificação | Professores e alunos ativos | Validação por marcos de módulos |

### 2. Leitura da matriz

Explique, em texto curto, o que a matriz mostrou. Não repita apenas os sinais. Identifique quais critérios puxam para controle, quais puxam para adaptáção e quais criam tensão.

| Critérios que pedem mais controle formal | A migração de dados históricos, a conformidade legal e regulatória e a integração com os processos financeiros exigem previsibilidade e controle estrito. |
| --- | --- |
| Critérios que pedem mais adaptação e feedback | A usabilidade da interface moderna, a experiência dos alunos e professores e a necessidade de evitar o risco de entregar um produto desalinhado com a operação diária. |
| Tensões principais percebidas | A rigidez necessária para garantir a segurança da migração de dados e finanças versus a necessidade de flexibilidade e adaptação no design da interface para atender os diferentes setores acadêmicos |

### 3. Abordagem escolhida

Marque a decisão da equipe e justifique tecnicamente. Se a escolha for híbrida, explique quais partes serão tratadas de modo mais preditivo e quais partes serão tratadas de modo mais adaptativo.

| Abordagem | Justicativa |
| --- | --- |
| Preditiva | marque se previsibilidade e controle predominam |
| ágil | marque se adaptação e feedback predominam |
| Híbrida |  |

Justi cativa técnica curta da escolha final: Optamos pela abordagem híbrida porque o projeto possui duas frentes distintas: a infraestrutura de banco de dados, migração histórica e integração financeira exigem controle rígido (preditivo), enquanto a criação dos módulos de atendimento, notas, frequência e interface para usuários demanda validações frequentes e melhorias contínuas (ágil).

<!-- página 4 -->

### 4. Ciclo de vida proposto

Desenhe ou descreva o ciclo de vida que será usado pela equipe. Ele deve ser coerente com a abordagem escolhida. Exemplos: fases sequenciais, ciclos iterativos, incrementos, sprints, piloto, validações com usuários ou combinação dessas formas.

| Etapa / ciclo | O que acontece | Entrega ou decisão esperada |
| --- | --- | --- |
| 1 Planejamento | Alinhamento de escopo, arquitetura e termos de abertura | Termo de abertura aprovado e EAP inicial. |
| 2 Desenvolvimento Iterativo | Construção incremental dos módulos de secretaria e notas | Versões parciais da interface para testes. |
| 3 Validação com Usuários | Testes de usabilidade com professores e coordenação | Ajustes de layout e aprovação dos módulos. |
| 4 Migração e Transição | Desligamento temporário, migração de dados e virada | Sistema 360 em produção e legado desativado. |

Representação visual simples do ciclo de vida:

### 5. Consequências práticas da escolha

Escolher uma abordagem muda o modo como a equipe vai trabalhar nas próximas aulas. Registre decisões operacionais, não apenas conceitos.

| Ponto de decisão | Consequência para o projeto da equipe |
| --- | --- |
| Como o termo de abertura vai registrar a condução do projeto | Explicará que o projeto adota o modelo híbrido para balancear a segurança regulatória/financeira com a agilidade operacional. |
| Se a decomposição será Estrutura Anal tica do Projeto (EAP), backlog ou estrutura híbrida | Estrutura híbrida (EAP para a infraestrutura de migração de dados e backlog para os módulos de interface dos usuários). |
| Com que frequência haverá validação com usuários | Por incremento de módulo entregue (ex: validação com professores após finalizar o lançamento de notas). |

<!-- página 5 -->

| Quais decisões precisam de aprovação formal | Escopo geral, custos de implantação e aceite da migração de dados financeiros e acadêmicos. |
| --- | --- |
| Quais partes exigem documentação mais forte | Requisitos legais, segurança de dados, conformidade e contratos de integração financeira. |
| Onde a equipe aceita adaptação e onde precisa de estabilidade | Estabilidade obrigatória na base de dados históricos e financeiros; aceitação de adaptação nos layouts e usabilidade de telas. |

### 6. Pontos que ainda podem exigir adaptação

Liste dúvidas, premissas ou eventos futuros que podem fazer a equipe revisar a abordagem escolhida.

| Ponto de adaptação | Sinal de alerta | Quando revisar |
| --- | --- | --- |
| Inconsistência de dados legados | Erros ou perdas de registros na conversão | Durante a Etapa 3 (Testes de migração) |
| Resistência operacional | Baixa adesão dos profissionais da secretaria | Na primeira validação com usuário |
| Prazos de integração técnica | Atrasos na comunicação com o setor financeiro | Marco de fechamento da Etapa 2 |

### 7. Preparação para a socialização final

Cada equipe terá aproximadamente cinco minutos para defender a decisão. A fala deve mostrar a passagem:

análise inicial do projeto → decisão preliminar → abordagem e ciclo de vida

Preparem a apresentação com base nos cinco pontos abaixo:

1. decisão preliminar da Aula 2: manter, reduzir, dividir ou reavaliar; Mantivemos o projeto

“Sistema Acadêmico 360” para eliminar a redundância do sistema legado e os processos manuais

2. alternativa considerada mais coerente e benefício principal esperado; O projeto como

proposto é o único capaz de unificar todos os setores em um ambiente moderno.

3. restrição, risco ou dependência que mais condiciona a condução; O maior risco é a janela

de tempo para migração e o desligamento dos sistemas fora do expediente.

<!-- página 6 -->

4. abordagem escolhida nesta aula e critério que mais pesou; Escolhemos a híbrida,

ponderando o controle preditivo na migração de dados e a agilidade adaptativa nas telas dos usuários

5. consequência prática para o próximo planejamento do projeto. O projeto usará EAP para

as fases estruturais e backlog de tarefas para os módulos visuais, com validações frequentes por entregas parciais

### 8. Registro das contribuições

| Integrante | Contribuição nesta atividade |
| --- | --- |
| José Joenk | Contribuição no brainstorming sobre o fluxo de transição entre sistema |
| Gustavo | Mapeamento dos riscos operacionais e pontos de adaptação para a migração |
| Hugo | Análise dos critérios da matriz e mapeamento dos requisitos de usabilidade |
| Luan Nick | Coordenação da escolha da abordagem híbrida e alinhamento |
| Nicolas Nass | Definição das frentes de escopo e estruturação dos requisitos de usabilidade |
| Vinicius Gilgen | Definição das frentes de escopo e estruturação dos requisitos de usabilidade |

### Checklist antes do envio

O a decisão da Aula 2 foi retomada explicitamente;

O a matriz contém sinais e evidências curtas, não apenas marcáveis soltas;

O a equipe não escolheu a abordagem por contagem mec nica de sinais;

O a justificativa diferencia controle formal, adaptá-lo e combiná-lo híbrida;

O o ciclo de vida proposto é coerente com a abordagem escolhida;

O há pelo menos três consequências práticas registradas;

O os pontos de adaptá-lo foram identi cados;

O todos os integrantes conhecem e conseguem defender a conclusão; O O

arquivo possui identificação, data e versão.

<!-- página 7 -->

### Entrega

Enviar um único documento em PDF, com nome sugerido: N1_CP03_EQUIPE-A_PROJETO_v0.1.pdf Adapte o identificador da equipe e o nome do projeto. Este documento é a entrega completa da atividade da Aula 3.
