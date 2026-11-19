<!-- Convertido de: entregas-equipe-2/Pesquisa_Central_U3_EQUIPE-2_SISTEMA-ACADEMICO-360_v0.1.pdf -->

<!-- página 1 -->

## Pesquisa Central – Unidade 3

Checkpoint N3-CP01: consolidação das pesquisas individuais aplicadas ao projeto

| Equipe | Equipe 2 (Karzones), chamada Equipe B no edital |
| --- | --- |
| Projeto | P2 – Sistema Acadêmico 360 (substituição e migração de sistema legado) |
| Disciplina | Gestão de Projetos, Engenharia de Software, Católica SC Joinville. Professor da disciplina |
| Coordenação | Luan Nick Ferreira da Silva |
| Data / Versão | 09/11/2026 – v0.1 (rascunho para a oficina de 12/11) |

**Integrantes, tópicos e entregas**

Os eventos da coluna central reproduzem o texto do edital (Seção 6, Equipe B – P2 Sistema Acadêmico 360), sem alteração.

| Integrante | Tópico | Evento do projeto | Entrega no checkpoint |
| --- | --- | --- | --- |
| Luan Nick Ferreira da Silva | Coordenação | Consolidação das cinco partes | Pacote único do checkpoint |
| Gustavo Henrique de Morais | Riscos | Análise inicial identifica duplicidade e inconsistência em 18% dos cadastros históricos | Registro e matriz de riscos, com resposta aos riscos prioritários |
| José Manoel Joenk | Liderança e pessoas | Único analista de banco de dados disponível é deslocado por três semanas | Acordo de equipe e resposta ao conflito de pessoas |
| Nicolas Nass | Comunicação e engajamento | Secretaria acadêmica reclama que decisões técnicas priorizam o setor financeiro | Plano de comunicação e ação de recuperação do stakeholder desalinhado |
| Vinícius Henrique Gilgen da Silva (gerente do projeto) | Execução, qualidade e mudanças | Nova exigência institucional de histórico digital com assinatura eletrônica | Solicitação de mudança formalizada, com análise de impactos |
| Hugo May Neto | Medição de desempenho | 85% dos registros validados; migração piloto atrasou 10 dias; treinamento atingiu 45% dos usuários | Relatório de status com indicadores acumulados e recomendação |

Sobre este documento. Reúne, na ordem dos tópicos do edital, as partes mais importantes das cinco pesquisas individuais. O texto de cada autor foi mantido. A Coordenação ajustou apenas a coesão (registro da linguagem, rótulos e referências), e todas as alterações estão listadas na Nota de consolidação, no fim. As Seções 6 e 7 são texto novo da Coordenação: mostram como as cinco respostas se cruzam e quais premissas a equipe adotou.

### 1. Riscos

Autor: Gustavo Henrique de Morais

**1.1 Tópico e resumo**

A gestão de riscos é o processo de identificar, analisar e planejar respostas para eventos incertos que podem afetar os objetivos de um projeto. Seu objetivo é antecipar problemas e reduzir seus impactos sobre o prazo, o orçamento e a qualidade das entregas. As principais etapas são:

- Identificação: reconhecer situações que podem prejudicar o projeto, identificando suas causas e

consequências.

- Análise: avaliar a probabilidade de cada risco acontecer e o impacto que ele pode causar.

- Priorização: classificar os riscos para determinar quais precisam de maior atenção.

- Resposta: definir ações para evitar, reduzir, transferir ou aceitar os riscos.

- Monitoramento: acompanhar os riscos durante a execução do projeto e verificar se as ações estão

funcionando.

**1.2 Aplicação ao projeto**

Durante a análise inicial da migração de dados, foi identificado que 18% dos cadastros históricos apresentam duplicidades ou inconsistências.

Equipe 2 (Karzones) – P2 Sistema Acadêmico 360 | Pesquisa Central – Unidade 3 | v0.1 Página 1

<!-- página 2 -->

Esse cenário representa um risco importante, pois o projeto precisa migrar 100% dos dados históricos de alunos, notas e informações financeiras sem corrupção. Caso os problemas não sejam tratados, poderão ocorrer perda de informações, cadastros duplicados no novo sistema, divergências nos históricos acadêmicos e atrasos na migração.

**1.3 Registro de riscos**

| ID | Risco identificado | Consequência |
| --- | --- | --- |
| R01 | Dados históricos corrompidos ou perdidos durante a migração. | Perda de informações importantes dos alunos. |
| R02 | Duplicidades nos cadastros não serem identificadas antes da migração. | Alunos com registros repetidos e informações conflitantes. |
| R03 | Inconsistências em notas e dados financeiros permanecerem no novo sistema. | Informações acadêmicas e financeiras incorretas. |
| R04 | O processo de limpeza e validação dos dados levar mais tempo que o previsto. | Atraso no cronograma e no marco da semana 14. |
| R05 | Necessidade de retrabalho e horas adicionais da consultoria de migração. | Aumento dos custos e pressão sobre o orçamento. |

**1.4 Matriz de probabilidade e impacto**

Escala de 1 a 3. Probabilidade: 1 = baixa, 2 = média, 3 = alta. Impacto: 1 = baixo, 2 = médio, 3 = alto. Pontuação = probabilidade × impacto.

| Risco | Probabilidade | Impacto | Pontuação | Prioridade |
| --- | --- | --- | --- | --- |
| R01 – Perda ou corrupção de dados | Média (2) | Alto (3) | 6 | Alta |
| R02 – Cadastros duplicados | Alta (3) | Alto (3) | 9 | Crítica |
| R03 – Informações incorretas | Alta (3) | Alto (3) | 9 | Crítica |
| R04 – Atraso na migração | Média (2) | Alto (3) | 6 | Alta |
| R05 – Aumento dos custos | Média (2) | Alto (3) | 6 | Alta |

Interpretação: os riscos R02 e R03 recebem prioridade máxima porque o problema já foi identificado em 18% dos cadastros históricos. Os demais também exigem acompanhamento, principalmente por seus possíveis impactos no prazo e no orçamento. Observação: as classificações de probabilidade e impacto são avaliações propostas para o planejamento da equipe, não medições já realizadas.

Equipe 2 (Karzones) – P2 Sistema Acadêmico 360 | Pesquisa Central – Unidade 3 | v0.1 Página 2

<!-- página 3 -->

**1.5 Respostas aos riscos**

| Risco | Ações | Estratégia |
| --- | --- | --- |
| R02 – Cadastros duplicados | • Realizar uma análise dos cadastros antes da migração. • Identificar registros duplicados por meio de identificadores e informações dos alunos. • Corrigir ou unificar registros duplicados, preservando o histórico correto. • Realizar uma nova verificação após a correção. | Mitigar o risco, reduzindo a quantidade de duplicidades antes da migração. |
| R03 – Informações acadêmicas e financeiras incorretas | • Conferir notas, matrículas, frequência e informações financeiras. • Comparar os dados do sistema antigo com os dados importados para o novo sistema. • Realizar testes de validação com representantes da secretaria e do setor financeiro. • Corrigir inconsistências antes de liberar o sistema para utilização. | Mitigar o risco por meio de verificações e testes de qualidade. |
| R01 – Perda ou corrupção de dados | • Criar cópias de segurança antes de iniciar a migração. • Realizar uma migração piloto. • Comparar a quantidade e a integridade dos registros entre os sistemas. • Manter o sistema legado disponível até a validação da migração. | Mitigar o risco e preparar uma possibilidade de recuperação caso ocorra uma falha. |
| R04 – Atraso na migração | • Priorizar a limpeza e a validação dos dados. • Acompanhar semanalmente o andamento das atividades. • Identificar antecipadamente tarefas que possam atrasar o marco da semana 14. • Reorganizar atividades e recursos caso necessário. | Mitigar o risco por meio do acompanhamento do cronograma. |
| R05 – Aumento dos custos | • Acompanhar as horas utilizadas pela consultoria de migração. • Registrar os custos adicionais relacionados à correção dos dados. • Utilizar a contingência prevista para problemas de qualidade dos dados, conforme aprovação da equipe responsável. • Evitar retrabalho por meio de validações antes da migração definitiva. | Mitigar o risco e controlar os gastos adicionais. |

**1.6 Relação com o cronograma e o orçamento**

O projeto possui duração planejada de 28 semanas, com um marco importante na semana 14, quando os dados devem estar migrados e validados. Além disso, o orçamento aprovado para o planejamento é de R$ 477.288, com teto máximo de R$ 480.000. Já existe uma reserva de contingência de R$ 13.600 destinada à baixa qualidade dos dados do sistema legado. Por isso, a equipe deve acompanhar os custos de correção e validação, evitando que o problema ultrapasse a reserva disponível ou comprometa o orçamento total. O critério de sucesso relacionado à migração é garantir que 100% dos dados históricos sejam transferidos sem corrupção.

**1.7 Justificativa**

A equipe deve priorizar a identificação e correção das duplicidades e inconsistências antes da migração definitiva, pois a qualidade dos dados é essencial para garantir a confiabilidade do Sistema Acadêmico 360, evitar retrabalho, respeitar o cronograma e manter o orçamento planejado.

### 2. Liderança e pessoas

Autor: José Manoel Joenk

**2.1 Conceitos essenciais**

1. A liderança em projetos orienta, motiva e influencia a equipe para alcançar os objetivos.

2. A gestão de pessoas envolve organizar responsabilidades, competências e disponibilidade dos integrantes.

3. O acordo de equipe define regras de convivência, responsabilidades e formas de trabalho.

4. Conflitos devem ser tratados rapidamente, com diálogo e foco na solução do problema.

5. O gerente deve acompanhar o desempenho e agir quando a falta de recursos ameaçar o projeto.

6. A liderança também envolve negociar prioridades e administrar mudanças na disponibilidade dos

profissionais. Referência conceitual: PMBOK, 7ª edição, especialmente os domínios de desempenho da equipe e dos recursos do projeto.

Equipe 2 (Karzones) – P2 Sistema Acadêmico 360 | Pesquisa Central – Unidade 3 | v0.1 Página 3

<!-- página 4 -->

**2.2 Aplicação ao projeto**

No projeto Sistema Acadêmico 360, o único analista de banco de dados disponível será deslocado por três semanas. Isso representa um problema de disponibilidade de recursos humanos e pode comprometer atividades importantes, principalmente a migração e a validação dos dados históricos. O impacto merece atenção porque:

- o projeto precisa migrar 100% dos dados históricos sem corrupção;

- a migração e a validação fazem parte do escopo;

- o cronograma possui 28 semanas e o caminho crítico não tem folga;

- o marco de dados migrados e validados está previsto para a semana 14.

Dados que faltam: não sabemos em quais semanas ocorrerá o deslocamento, quais tarefas específicas serão afetadas, se existe outro profissional capacitado para substituir o analista ou se o fornecedor pode oferecer apoio adicional. Também não está informado se os demais integrantes possuem conhecimento técnico suficiente para assumir atividades de banco de dados, e isso precisa ser verificado antes da redistribuição. Portanto, não é possível afirmar que haverá atraso, mas existe risco de comprometimento do cronograma e da qualidade da migração. O gerente do projeto deve conversar com a equipe, avaliar as atividades afetadas, negociar prioridades e buscar uma alternativa sem comprometer a integridade dos dados.

**2.3 Acordo de equipe proposto**

Diante da ausência do analista de banco de dados, a equipe estabelece as seguintes regras:

| Regra | Compromisso da equipe |
| --- | --- |
| Comunicação | Informar imediatamente dificuldades causadas pela ausência do analista. |
| Responsabilidades | Não assumir tarefas técnicas sem a competência necessária. |
| Priorização | Priorizar atividades essenciais à migração e à integridade dos dados. |
| Colaboração | Os integrantes devem apoiar as atividades compatíveis com suas competências. |
| Decisões | O gerente do projeto coordenará a redistribuição de prioridades. |
| Acompanhamento | Monitorar os impactos nas atividades e no marco da semana 14. |

**2.4 Resposta ao conflito de pessoas**

Problema identificado: ausência temporária do único analista de banco de dados, gerando possível disputa por recursos e prioridades. Plano de resposta:

1. Identificar: levantar quais atividades dependem exclusivamente do analista.

2. Conversar: reunir a equipe para entender as dificuldades e ouvir sugestões.

3. Avaliar: verificar quais tarefas podem ser redistribuídas sem comprometer a qualidade.

4. Negociar: reorganizar prioridades e buscar apoio técnico, caso disponível.

5. Decidir: o gerente do projeto, Vinícius, coordenará as ações e acompanhará os impactos.

6. Monitorar: verificar se a ausência compromete o cronograma ou a migração dos dados.

Se não houver alternativa viável, será necessário avaliar formalmente o impacto no cronograma e comunicar a situação aos responsáveis pelo projeto.

**2.5 Justificativa**

A proposta foi escolhida porque a ausência do único analista de banco de dados pode comprometer uma atividade crítica do Sistema Acadêmico 360. Um acordo de equipe e uma resposta colaborativa ao conflito ajudam a organizar as responsabilidades, preservar a qualidade da migração e reduzir os riscos de atraso.

Equipe 2 (Karzones) – P2 Sistema Acadêmico 360 | Pesquisa Central – Unidade 3 | v0.1 Página 4

<!-- página 5 -->

### 3. Comunicação e engajamento

Autor: Nicolas Nass

**3.1 Tópico e resumo conceitual**

Na gestão de projetos, gerenciar a comunicação consiste em garantir que a informação certa chegue à pessoa certa, no momento certo e pelo canal apropriado, enquanto gerenciar o engajamento dos stakeholders significa manter as partes interessadas participando ativamente das decisões que as afetam, prevenindo resistência operacional e retrabalho (PROFESSOR, 2026c; PMI, 2021). Segundo a matriz Poder × Interesse trabalhada na iniciação do projeto (PROFESSOR, 2026a), stakeholders posicionados no quadrante de baixo poder formal sobre orçamento e escopo, mas alto interesse no resultado diário (como os usuários operacionais), exigem a estratégia de manter informados e consultados continuamente sobre cada entrega que impacte sua rotina. De acordo com o Guia PMBOK (PMI, 2017; PMI, 2021), falhas de comunicação ou percepção de assimetria de prioridade entre setores provocam desalinhamento e queda no nível de engajamento (migrando de apoiador para neutro ou resistente), o que demanda três ações coordenadas: planejamento (definir quem recebe o quê, com que frequência e por qual canal), alinhamento (comunicar decisões técnicas e restrições de forma transparente) e participação (envolver o stakeholder desalinhado na coautoria e validação das entregas).

**3.2 Diagnóstico do evento nos artefatos das Unidades 1 e 2**

A reclamação da Secretaria Acadêmica reflete decisões estruturais registradas no Dossiê de Iniciação (N1) e no Relatório da Unidade 2 (N2) que deram maior visibilidade imediata ao setor Financeiro sem a devida comunicação à Secretaria:

- Papel e critério de sucesso da Secretaria (Dossiê N1): a Secretaria foi mapeada como Cliente/Usuário

Final no quadrante Baixo Poder / Alto Interesse, sendo dona do primeiro critério de sucesso verificável do projeto: reduzir em pelo menos 80% o tempo gasto na emissão de documentos por meio de templates (teste cronometrado). Além disso, já no checkpoint N1-CP03 (Aula 3), a equipe havia registrado o alerta “Resistência operacional – baixa adesão dos profissionais da secretaria”.

- Caminho crítico versus folga das configurações (Relatório U2, Seção 1): no cronograma de 28

semanas (17 atividades), a atividade D1 (Integração financeira, semanas 14 a 16,5) pertence ao caminho crítico (folga = 0) e abre a Release 2 (Sprint 5). Já as configurações voltadas à Secretaria, C1 (Cadastro, 2,5 sem.), C2 (Matrículas, 3 sem.) e C4 (Histórico e documentos, 3,5 sem.), executadas entre as semanas 7 e 10,5 (Sprints 3 e 4), possuem de 3,5 a 4,5 semanas de folga. Sem comunicação clara sobre a lógica da rede de atividades, a Secretaria interpreta a atenção dada ao caminho crítico (migração B1–B3 e integração financeira D1) como favoritismo ao setor Financeiro.

- Ameaça de corte sobre C4 no orçamento (Relatório U2, Seção 9): o orçamento total é de R$ 477.288

(teto de R$ 480.000 e folga de R$ 2.712). No plano de contingência para corte de 10% no teto (para R$ 432.000), a Medida nº 4 prevê adiar C4 (Histórico e documentos, economia de R$ 6.300) para depois da operação inicial, obrigando a Secretaria a continuar consultando o legado, ao passo que a integração financeira (D1) foi blindada por estar no caminho crítico.

- Agrupamento na Matriz RACI e nas revisões de Sprint (Relatório U2, Seções 2, 3 e 6): os

representantes da Secretaria e do Financeiro compartilham uma alocação única de 20% (2 pessoas = 448 h totais, custo R$ 0 para o projeto) nas semanas 1 a 28 e participam juntos da revisão ao fim de cada sprint (a cada 3,5 semanas). Na Matriz RACI, ambos foram agrupados na coluna genérica “Cliente (representantes)”, figurando apenas como Consultados (C) em C1 a C4.

- Dados ausentes nos documentos e premissa adotada: os documentos da N1 e da N2 não informam em

qual semana exata a queixa ocorreu nem como as 448 h se dividem entre os dois representantes. Adota-se como premissa que o evento ocorre na transição da Release 1 para a Release 2 (entre as semanas 10,5 e 14), quando C1–C4 terminam e o foco técnico passa para a Integração Financeira (D1), e que as 448 h dividem-se igualmente (224 h para a Secretaria e 224 h para o Financeiro).

**3.3 Plano de comunicação do projeto**

Para estruturar o fluxo de informações ao longo das 28 semanas (8 sprints de 3,5 semanas) e alinhar as frentes preditiva e ágil, estabelece-se o plano abaixo.

Equipe 2 (Karzones) – P2 Sistema Acadêmico 360 | Pesquisa Central – Unidade 3 | v0.1 Página 5

<!-- página 6 -->

| Stakeholder (Poder × Interesse) | O que comunicar | Canal e frequência | Responsável | Objetivo de engajamento |
| --- | --- | --- | --- | --- |
| Secretaria Acadêmica (Baixo Poder / Alto Interesse – Cliente/Usuário) | Incrementos de C1 (Cadastro), C2 (Matrículas) e C4 (Templates); evolução da meta de -80% no tempo de emissão e status de B1–B3. | Oficina prática em homologação (separada da pauta financeira). Quinzenal nas Sprints 3 e 4 (sem. 7 a 14) e ao fim de cada Sprint (3,5 sem.). | Dev 1, Dev 2 e Gerente (Vinícius) | Recuperar engajamento; garantir coautoria nos templates e validação ativa (Papel C e R). |
| Setor Financeiro (Consultado / Usuário) | Regras de cobrança, andamento de D1 (Integração financeira) e validação de registros financeiros migrados (B3/D2). | Reunião técnica de integração financeira. Ao fim de cada Sprint (3,5 sem.) e semanal na Sprint 5 (sem. 14 a 16,5). | Analista de BD, Devs e Gerente | Garantir precisão técnica no caminho crítico sem sobrepor a pauta da Secretaria. |
| Direção Escolar Municipal (Alto Poder / Alto Interesse – Patrocinador) | Status dos marcos (sem. 7, 14, 21 e 28), orçamento (R$ 477.288 / teto R$ 480.000), contingência (R$ 30.000), reserva (R$ 22.728) e mudanças. | Relatório Executivo de Status + Reunião de Governança. Ao fim de cada Sprint (3,5 sem.) e extraordinariamente em decisões de escopo ou reserva. | Gerente do Projeto (Vinícius Gilgen) | Gerenciar de perto; assegurar patrocínio e aprovação formal (Papel A na RACI). |
| Coordenação e Professores (Baixo Poder / Alto Interesse – Usuários) | Incrementos do Módulo Docente (C3 – Notas e frequência, sem. 7 a 11) e cronograma de treinamento (E1–E3, sem. 22 a 26). | Demonstração guiada de protótipo / homologação e comunicados. Entregas de C3 (Sprints 3–4), homologação D3 (sem. 19–21) e treinamento (sem. 22–26). | Desenvolvedore s e Analista de Testes | Manter informados e validar usabilidade (reflexo instantâneo de notas para alunos). |
| Setor Jurídico e Conformidade (Alto Poder / Baixo Interesse) | Requisitos legais de emissão documental, validade de históricos e proteção de dados na migração do legado. | Parecer formal / ponto de controle documental. Marco A3 (sem. 7), conclusão de C4 (sem. 10,5), D3 (sem. 21) e mudanças regulatórias. | Gerente do Projeto (Vinícius Gilgen) | Manter satisfeito; evitar bloqueio legal ou invalidação de documentos. |
| Equipe Técnica e Consultoria (Devs, BD, Testes, Infra e Fornecedor) | Quadro de backlog da sprint, janelas fixas de ambiente (sem. 9 a 12), desvios na migração e controle das 3.288 h alocadas. | Checkpoint técnico semanal + Quadro de Backlog. Semanal e na abertura e fechamento de cada Sprint (3,5 sem.). | Gerente do Projeto (Vinícius Gilgen) | Sincronizar dependências entre caminho crítico (B1–B3, D1) e configurações (C1–C4). |

**3.4 Ação de recuperação do stakeholder desalinhado (Secretaria)**

Para neutralizar a percepção de que as decisões técnicas priorizam o Financeiro e recuperar o engajamento da Secretaria Acadêmica sem estourar o orçamento (R$ 477.288) nem atrasar os marcos (semanas 7, 14, 21 e 28), a equipe executa quatro ações corretivas:

1. Desmembramento das revisões de Sprint (custo R$ 0): separar as revisões de fim de sprint (a cada 3,5

semanas) em duas agendas independentes dentro das 448 horas (20% de dedicação) já alocadas aos representantes do cliente: uma Oficina de Validação da Secretaria (focada em C1, C2 e C4) e uma Revisão Técnica Financeira (focada em B3 e D1). Isso impede que discussões técnicas de banco de dados e cobrança dominem o tempo de escuta da Secretaria.

2. Alinhamento transparente sobre o caminho crítico e blindagem de C4: o Gerente do Projeto (Vinícius,

alocado a 50% / 560 h) realiza uma sessão de transparência com a Secretaria demonstrando que a prioridade operacional dada à migração (B1–B3) e à integração financeira (D1) decorre exclusivamente da dependência lógica sem folga no caminho crítico, e que o Dev 2 está dedicado em 100% nas semanas 7 a 10,5 para concluir C4 (Histórico e documentos, 3,5 semanas) antes mesmo do início de D1 (semana 14). Formaliza-se também junto à Direção que, mantido o teto de R$ 480.000, a atividade C4 jamais será adiada (afastando o temor gerado pela Medida 4 de corte hipotético).

3. Coautoria nos templates e teste cronometrado antecipado: incluir o representante da Secretaria em

sessões quinzenais práticas com o Dev 2 (semanas 7 a 10,5) e com o Analista de Testes (na preparação dos casos de teste nas semanas 12 a 14 e na execução em D2/D3 nas semanas 16,5 a 21) para desenhar os templates documentais e realizar medições cronometradas parciais. Assim, a Secretaria vivencia na prática a construção da meta de redução de 80% no tempo de emissão de documentos antes da homologação final na semana 21.

Equipe 2 (Karzones) – P2 Sistema Acadêmico 360 | Pesquisa Central – Unidade 3 | v0.1 Página 6

<!-- página 7 -->

4. Atualização dos artefatos anteriores (rastreabilidade N1/N2 para N3): atualizar a Matriz RACI (Seção 6

da U2) desmembrando a coluna “Cliente (representantes)” em “Representante da Secretaria” e “Representante do Financeiro”, atribuindo à Secretaria o papel de Consultada obrigatória (C) em C1, C2 e C4 e Executante de validação (R) no teste cronometrado de D3 (semana 21). No Registro de Riscos, vincular o controle do risco de “Resistência operacional da secretaria” (N1-CP03) ao indicador de aceite parcial dos templates nas Sprints 3 e 4.

**3.5 Justificativa**

Optou-se por separar os rituais de validação da Secretaria e do Financeiro e antecipar a coautoria nos templates de documentos (atividade C4) porque, embora a Secretaria tenha baixo poder formal sobre o orçamento, ela detém alto interesse operacional e responde diretamente pelo principal critério de sucesso de negócio do projeto (reduzir em 80% o tempo de emissão documental), permitindo recuperar seu engajamento dentro das 448 horas já alocadas ao cliente sem consumir a folga orçamentária de R$ 2.712 nem atrasar o caminho crítico de 28 semanas.

### 4. Execução, qualidade e mudanças

Autor: Vinícius Henrique Gilgen da Silva (gerente do projeto)

**4.1 Tópico e resumo**

Executar é transformar o plano em entrega real e conferir se o resultado atende ao que foi definido. Três ideias sustentam o tópico. A primeira é a execução, em que se coordenam atividades, recursos e responsáveis (PMBOK 6, processo 4.3). A segunda é a qualidade: um critério de aceite verifica se a entrega cumpre o requisito, e não só se foi concluída (processos 8.3, Controlar a Qualidade, e 5.5, Validar o Escopo). A terceira é a mudança. Ela é tratada no Controle Integrado de Mudanças (processo 4.6): toda solicitação é registrada, tem o impacto analisado em escopo, prazo, custo, risco e qualidade, e só então é aprovada ou rejeitada por quem tem autoridade. Se aprovada, as linhas de base são atualizadas e os envolvidos são informados. Aceitar uma mudança sem essa análise é o caminho mais curto para estourar o cronograma, como alerta o slide da Aula 15.

**4.2 O evento e como o interpretamos**

A instituição passa a exigir histórico digital com assinatura eletrônica. O escopo da N1 prevê “históricos” e “documentos” (atividade C4, Configurar histórico e documentos), mas não prevê assinatura eletrônica. Por isso isto é mudança de escopo, e quem aprova mudança de escopo e orçamento é a Direção (Patrocinador), conforme o Termo de Abertura. Premissa: o pedido chega antes da semana 7, quando o escopo ainda está em validação (A3) e a licença da plataforma ainda não foi contratada. Se chegar depois do início de C4, há retrabalho e o custo sobe.

**4.3 Solicitação de mudança formalizada**

| Campo | Preenchimento |
| --- | --- |
| ID / data | SM-01 / 08/11/2026 |
| Solicitante | Instituição (exigência institucional) |
| Responsável pela análise | Vinícius Gilgen (gerente) |
| Aprovador | Direção escolar municipal (Patrocinador) |
| Descrição | Emitir o histórico escolar em formato digital com assinatura eletrônica, mantendo a validade dos documentos já emitidos. |
| Tipo | Mudança de escopo (nova entrega dentro de C4), com efeito em testes e na validação dos dados migrados. |
| Justificativa | Exigência institucional. Sem ela, o histórico emitido pelo novo sistema não atende à regra da instituição. |
| Situação | Em análise, aguardando decisão da Direção. |

Equipe 2 (Karzones) – P2 Sistema Acadêmico 360 | Pesquisa Central – Unidade 3 | v0.1 Página 7

<!-- página 8 -->

**4.4 Análise de impactos**

| Dimensão | Impacto | Base no plano |
| --- | --- | --- |
| Escopo | C4 passa a incluir fluxo de assinatura, verificação de autenticidade e emissão digital do histórico. A EAP e o backlog (épico Secretaria) são atualizados. | Dossiê N1, seções 5 e 6 |
| Prazo | C4 tem 3,5 semanas de folga de calendário (termina na semana 10,5 e D1 só começa na 14), mas a folga de pessoas é menor: com 2 desenvolvedores, a margem é de só 0,5 semana cada, 1 semana-desenvolvedor no total. Acima disso, D1 atrasa e, como o caminho crítico não tem folga, o prazo de 28 semanas é rompido. | U2, seções 1 e 5 |
| Custo | A mudança não cabe na folga até o teto (R$ 2.712). A contingência (R$ 30.000) só cobre os 3 riscos identificados e não pode ser usada. A fonte correta é a reserva gerencial (R$ 22.728), com aprovação do cliente. | U2, seções 7 e 8 |
| Qualidade | A exigência não pode anular o critério de sucesso de reduzir em 80% o tempo de emissão de documentos. Também é preciso garantir que o histórico migrado esteja íntegro antes de ser assinado. | Dossiê N1, seção 1.6 |
| Riscos | Três riscos novos: (1) o Jurídico, de alto poder e baixo interesse, não define a tempo o nível de assinatura exigido; (2) a plataforma escolhida não oferece assinatura nativa; (3) dados inconsistentes (os 18% duplicados ou inconsistentes) entram em documento assinado, o que agrava o problema. | N1, seção 4.2; evento de Riscos |
| Pessoas | Exige tempo do analista de BD, que é o mesmo recurso do evento de Pessoas (deslocamento de 3 semanas). Os dois eventos precisam ser planejados juntos. | U2, seção 3 |
| Comunicação | O Jurídico precisa ser envolvido de perto. A secretaria, que reclama de priorização do financeiro, é a maior beneficiada pela emissão digital do histórico. | N1, seção 4.2 |
| Treinamento | O fluxo de assinatura entra no conteúdo do treinamento (E1 a E3). Premissa: sem custo extra no contrato de R$ 30.000. | U2, seção 4 |

**4.5 Cenários e custo**

Valores internos calculados com as horas e os valores por hora da U2 (desenvolvedor R$ 45, analistas R$ 40, gerente R$ 80). O esforço é estimativa nossa, pois as estimativas do dossiê continuam como “A est.” e a plataforma ainda não foi escolhida.

| Item | Cenário A (assinatura nativa ou por configuração) | Cenário B (integração com serviço externo) |
| --- | --- | --- |
| Desenvolvimento em C4 | 1 semana-desenvolvedor: R$ 1.800 | 3 semanas-desenvolvedor: 1 dentro da margem (R$ 1.800) e 2 excedentes |
| Gerente (decisão e alinhamento com Jurídico) | 0,5 semana: R$ 800 | R$ 800 |
| Analista de testes (D2 e D3) | 1 semana: R$ 1.600 | R$ 1.600 |
| Analista de BD (validar histórico migrado) | 0,5 semana: R$ 800 | R$ 800 |
| Efeito no prazo | Nenhum: cabe na margem de 1 semana-desenvolvedor | D1 atrasa 1 semana (2 semanas-desenvolvedor excedentes ÷ 2 desenvolvedores); prazo vai a 29 semanas. O custo da semana é R$ 8.440 em pessoas. |
| Serviço ou certificado de assinatura | A cotar (pode estar na licença) | A cotar, fora do total abaixo |
| Total interno estimado | R$ 5.000 | R$ 13.440 (R$ 1.800 + R$ 3.200 + R$ 8.440) |
| Reserva gerencial depois da mudança | R$ 17.728 (cobre cerca de 2,1 semanas de atraso) | R$ 9.288 (cobre cerca de 1,1 semana) |
| Orçamento total | Permanece R$ 477.288, abaixo do teto de R$ 480.000 | Permanece R$ 477.288 só se o custo externo couber na reserva restante |

Conflito com o plano de corte. Se o teto cair 10% (R$ 432.000), a medida 4 da U2 prevê adiar C4 para depois da operação inicial. Com esta mudança, C4 deixa de poder ser adiado, e o corte precisaria ser refeito.

**4.6 Critérios de aceite da mudança**

1. Integridade: em amostra definida com a secretaria, 100% dos históricos migrados (conferidos pelo teste

de contagem) são emitidos em formato digital sem perda de campo.

Equipe 2 (Karzones) – P2 Sistema Acadêmico 360 | Pesquisa Central – Unidade 3 | v0.1 Página 8

<!-- página 9 -->

2. Assinatura: o documento emitido traz assinatura eletrônica no nível que o Jurídico definir, e qualquer

alteração posterior no documento é detectável.

3. Desempenho: o teste cronometrado antes e depois continua mostrando redução de pelo menos 80% no

tempo de emissão, agora com a assinatura incluída.

4. Validade: o Jurídico confirma por escrito que os documentos emitidos mantêm a validade.

5. Autonomia: após o treinamento, a secretaria emite e assina o histórico sem apoio da TI (lista de presença

assinada e emissão de teste). Os critérios 1 a 3 entram nos testes de D2 e na validação com usuários de D3. O critério 4 é o aceite formal do Patrocinador, no marco “Nova plataforma validada”, na semana 21.

**4.7 Recomendação e decisão pedida à Direção**

Recomendação: aprovar com condições o Cenário A, com autorização antecipada de até R$ 5.000 da reserva gerencial, sob três condições:

- O Jurídico define até a semana 7 qual nível de assinatura é exigido (simples, avançada ou qualificada,

conforme a Lei 14.063/2020), porque o custo e o esforço dependem dessa resposta.

- A assinatura eletrônica entra como requisito obrigatório na escolha e no contrato da plataforma (semana 7),

que ainda não está definida. É o momento mais barato para absorver a mudança.

- Se a cotação ou a análise técnica indicar o Cenário B, o pedido volta à Direção com a opção de ampliar o

prazo para 29 semanas ou reduzir escopo em outro ponto. Se aprovada, atualizamos o escopo, a EAP e o backlog, o cronograma de C4, o RACI, o orçamento (uso da reserva) e o registro de riscos, e comunicamos Jurídico, secretaria, financeiro e equipe de TI.

**4.8 Premissas e dúvidas**

- Premissa: o pedido chega antes da semana 7.

- Premissa: os esforços da seção 4.5 são estimativas da equipe, a validar com o fornecedor da plataforma.

- Premissa: o treinamento absorve o novo conteúdo sem custo adicional.

- Dúvida: qual nível de assinatura a instituição exige, e se a exigência cobre também históricos já emitidos.

- Dúvida: o custo de serviço ou certificado de assinatura, que não consta nos fornecedores da U2.

- Dúvida: se a plataforma escolhida oferece assinatura nativa.

**4.9 Justificativa**

Recomendamos o Cenário A porque cumpre a exigência sem mover o prazo de 28 semanas nem o teto de R$ 480.000, usando a reserva gerencial (a única fonte permitida pelas regras da U2) e aproveitando que a plataforma ainda não foi contratada.

### 5. Medição de desempenho

Autor: Hugo May Neto

Recomendação (conclusão primeiro): CORRIGIR. O desvio é recuperável com a reserva gerencial e não encosta no teto de R$ 480.000. Mas o caminho crítico não tem folga, então só seguir já garantiria atraso.

**5.1 Tópico e resumo**

Medir desempenho é comparar o realizado com a linha de base (prazo, custo, escopo e qualidade), calcular o desvio e decidir o que fazer. No PMBOK isso é o monitoramento e controle: indicador sem ação não serve. A lógica aplicada:

- Base de comparação: a linha de base de prazo e de custo do plano da Unidade 2.

- Desvio: quanto o realizado fugiu do previsto e se passou do gatilho combinado antes.

- Ação corretiva: entra só quando o desvio passa do gatilho. Dentro dele, segue e acompanha.

- Valor agregado: SPI (prazo) e CPI (custo) são os índices clássicos. Abaixo de 1 é ruim.

**5.2 Aplicação ao projeto**

Evento: 85% dos registros validados, migração piloto 10 dias atrasada e treinamento em 45% dos usuários.

Equipe 2 (Karzones) – P2 Sistema Acadêmico 360 | Pesquisa Central – Unidade 3 | v0.1 Página 9

<!-- página 10 -->

**Indicadores acumulados**

| Indicador | Situação | Leitura | Status |
| --- | --- | --- | --- |
| Registros validados | 85% | O critério de sucesso é 100% migrado sem corrupção (marco da semana 14). Faltam 15%. | Atenção |
| Migração piloto | 10 dias de atraso | A cadeia de migração (B1 a B3) está no caminho crítico, sem folga. | Crítico |
| Treinamento | 45% dos usuários | O plano não traz meta intermediária, então não é possível classificar como bom ou ruim. | Sem meta |

**Desvio de prazo e custo**

- Sem folga no caminho crítico, 10 dias úteis (2 semanas) empurram o projeto de 28 para cerca de 30

semanas se ninguém recuperar.

- No relatório da Unidade 2, cada semana de atraso no caminho crítico custa de R$ 5.040 a R$ 8.440 em

pessoas. Em 2 semanas, são R$ 10.080 a R$ 16.880.

- A reserva gerencial é de R$ 22.728. No pior caso sobram R$ 5.848. Ela aguenta cerca de 2,7 semanas no

ritmo mais caro e 4,5 no mais barato.

- A reserva já está dentro dos R$ 477.288 do orçamento total, então usá-la não passa o teto. Mas o cliente

precisa aprovar o uso (RACI da Unidade 2).

**Ações corretivas, por prioridade**

1. Fechar os 15% de validação que faltam, começando pelos registros duplicados e inconsistentes (o evento

de Riscos, 18% dos cadastros). A contingência de R$ 13.600 para qualidade dos dados já cobre esse risco.

2. Proteger o caminho crítico: a migração tem prioridade nas janelas de ambiente.

3. Definir meta de treinamento por semana e convocar os 55% que faltam. Se não andar, treinar só

multiplicadores com material gravado (corte nº 2 da lista, R$ 15.000 de economia).

4. Registrar o uso da reserva e pedir a aprovação da Direção.

**Gatilhos para mudar a recomendação**

- Atraso passa de cerca de 2,7 semanas: a reserva acaba. Vira reduzir, com pedido de mudança para a

Direção (por exemplo, adiar C4, histórico e documentos).

- Realizado de pessoas passa 5% do previsto: rever alocação, porque a folga de R$ 2.712 até o teto não

absorve aumento estrutural.

- Migração mostra corrupção de dados: vira pausar, porque 100% sem corrupção é inegociável.

**5.3 Premissas e dúvidas**

- Premissa: os “10 dias” são úteis (2 semanas), o cenário mais pesado. Se forem corridos (cerca de 1,4

semana), o custo cai para R$ 7.200 a R$ 12.057.

- Premissa: o custo do atraso é cálculo próprio (semanas × custo por semana do relatório da Unidade 2).

Não é número oficial do projeto.

- Dúvida: o evento não diz em que semana o projeto está nem a meta de treinamento. No plano, o

treinamento só roda nas semanas 22 a 26, então 45% com a migração atrasada parece fora de ordem. Para a oficina de 12/11, a Coordenação (Luan Nick) adotou a semana 13 e a leitura de capacitação antecipada, conforme a Seção 7.

- Falta: SPI e CPI não podem ser calculados sem o valor planejado e o custo real acumulado.

**5.4 Justificativa**

Escolhi corrigir porque o desvio se recupera dentro da reserva e não ameaça o teto, mas, com o caminho crítico sem folga, seguir sem agir garantiria atraso, e reduzir ou pausar seriam exagero com 85% dos dados validados.

Equipe 2 (Karzones) – P2 Sistema Acadêmico 360 | Pesquisa Central – Unidade 3 | v0.1 Página 10

<!-- página 11 -->

### 6. Visão integrada dos cinco tópicos

Texto da Coordenação: Luan Nick Ferreira da Silva

Os cinco eventos atingem o mesmo projeto, de modo que as respostas se cruzam. A tabela mostra os principais cruzamentos, para a equipe tratá-los juntos na oficina de 12/11.

| Ponto de cruzamento | Quem trata | O que se observa |
| --- | --- | --- |
| Analista de banco de dados | José, Gustavo, Vinícius, Hugo | O mesmo profissional é afetado por quatro eventos: a ausência de três semanas, a limpeza e a validação dos 18% de cadastros, a validação do histórico assinado (0,5 semana na SM-01) e a migração piloto atrasada. A cadeia B1–B3 está no caminho crítico, sem folga. |
| Reserva gerencial (R$ 22.728) | Hugo, Vinícius | Hugo estima R$ 10.080 a R$ 16.880 para duas semanas de atraso. Vinícius pede até R$ 5.000 para o Cenário A. Somados, ficam entre R$ 15.080 e R$ 21.880, e sobram de R$ 7.648 a R$ 848 na reserva. Com o Cenário B (R$ 13.440), a soma passa de R$ 23.520 e supera a reserva, e o pedido volta à Direção. Somas feitas pela Coordenação com os valores de cada autor, supondo que as duas despesas saiam da mesma reserva. |
| Contingência (R$ 13.600 para qualidade dos dados) | Gustavo, Hugo, Vinícius | Gustavo e Hugo apontam essa contingência para tratar os 18% de cadastros. Vinícius lembra que a contingência de R$ 30.000 cobre só os três riscos já identificados e não paga a assinatura eletrônica. |
| Secretaria e atividade C4 | Nicolas, Vinícius | Nicolas propõe que C4 nunca seja adiada, e a SM-01 de Vinícius também impede adiá-la. Os dois textos levam à mesma conclusão: a medida 4 do plano de corte da U2 precisa ser refeita. Vinícius ainda aponta a Secretaria como a maior beneficiada pela emissão digital do histórico, argumento útil no plano de comunicação. |
| Jurídico | Vinícius, Nicolas | O Jurídico precisa definir até a semana 7 o nível de assinatura exigido. O plano de comunicação de Nicolas já prevê parecer formal desse setor no marco A3 (semana 7), e a decisão pode entrar nesse ponto de controle. |

### 7. Premissas adotadas para a oficina de 12/11

Os documentos de origem deixam alguns dados em aberto. Como o caso é fictício, a Coordenação adotou as premissas abaixo, declaradas como premissas da equipe, e não como fatos informados pelo cliente. Elas podem ser revisadas na oficina. Se mudarem, os textos que dependem delas devem ser revistos.

| Ponto | Premissa adotada | Quem usa |
| --- | --- | --- |
| Semana dos eventos | Riscos (18% de cadastros duplicados ou inconsistentes) e Pessoas (ausência do analista de BD por três semanas, da semana 7 à 10) ocorrem na semana 7, quando a preparação dos dados (B1) começa. A mudança de assinatura eletrônica chega até o início da semana 7, antes do aceite do escopo (A3) e da assinatura do contrato da licença. A queixa da Secretaria ocorre entre as semanas 10,5 e 14. As métricas do projeto são medidas na semana 13, perto do marco dos dados migrados e validados. | Gustavo, José, Vinícius, Nicolas, Hugo |
| Tarefas só do analista de BD | B1 a B3 (preparar, migrar e validar dados). Na ausência dele, a consultoria de migração (R$ 85.000, semanas 8 a 14) apoia a migração, e a semana 7, anterior ao início da consultoria, fica sem cobertura técnica. | José, Gustavo |
| Meta de treinamento | O plano não traz meta intermediária. A equipe propõe, para formalizar, 50% dos usuários-chave capacitados até a semana 14 e 100% até a semana 26. Os 45% medidos na semana 13 se referem a essa capacitação antecipada. | Hugo |
| SPI e CPI | Não são calculados. Falta o valor planejado e o custo real acumulado, e a equipe não os inventa. A recomendação usa o desvio de prazo e custo estimado a partir do relatório da Unidade 2. | Hugo |
| Assinatura eletrônica | O Jurídico define o nível avançado (Lei 14.063/2020) até a semana 7, e a plataforma escolhida oferece assinatura nativa. Isso sustenta o Cenário A. O custo do serviço ou certificado segue como “a cotar”. | Vinícius |
| 448 h dos representantes | Divididas igualmente: 224 h para a Secretaria e 224 h para o Financeiro. | Nicolas |
| “10 dias” de atraso | Dias úteis, ou seja, 2 semanas, o cenário mais pesado. | Hugo |

Equipe 2 (Karzones) – P2 Sistema Acadêmico 360 | Pesquisa Central – Unidade 3 | v0.1 Página 11

<!-- página 12 -->

| 8. Contribuição por integrante |  |
| --- | --- |
| Integrante | Contribuição neste documento |
| Luan Nick Ferreira da Silva | Coordenação: recebeu as cinco pesquisas, padronizou o texto, escreveu as Seções 6 e 7 e montou este documento. |
| Gustavo Henrique de Morais | Registro de riscos, matriz de probabilidade e impacto e respostas aos riscos prioritários. |
| José Manoel Joenk | Acordo de equipe e resposta ao conflito de pessoas. |
| Nicolas Nass | Plano de comunicação e ação de recuperação da Secretaria Acadêmica. |
| Vinícius Henrique Gilgen da Silva | Solicitação de mudança SM-01, com análise de impactos, cenários e recomendação. |
| Hugo May Neto | Relatório de status, indicadores acumulados e recomendação CORRIGIR. |

### Referências

BRASIL. Lei nº 14.063, de 23 de setembro de 2020. Dispõe sobre o uso de assinaturas eletrônicas em interações com entes públicos, em atos de pessoas jurídicas e em questões de saúde. Brasília, DF: Presidência da República, 2020. EQUIPE 2 (KARZONES). N1-FINAL – Dossiê de Iniciação do Projeto, v1.0. Joinville, 23 set. 2026. EQUIPE 2 (KARZONES). Relatório da Unidade 2 – P2 Sistema Acadêmico 360. Joinville, 26 out. 2026. EQUIPE 2 (KARZONES). Contexto do projeto P2 – Sistema Acadêmico 360: Unidade 3. Material de orientação da equipe, 2026. PROFESSOR DA DISCIPLINA. Aula 05 – Stakeholders e governança (N1-CP05a): Gestão de Projetos. Joinville: Centro Universitário Católica de Santa Catarina, 2026a. PROFESSOR DA DISCIPLINA. Edital do Projeto – Unidade 3: Gestão de Projetos. Joinville: Centro Universitário Católica de Santa Catarina, 2026b. PROFESSOR DA DISCIPLINA. Aula 15 – Retomada de N1, N2 e N3 e Base Conceitual: Gestão de Projetos. Joinville: Centro Universitário Católica de Santa Catarina, 2026c. PROJECT MANAGEMENT INSTITUTE (PMI). Um guia do conhecimento em gerenciamento de projetos (Guia PMBOK). 6. ed. Newtown Square: PMI, 2017. PROJECT MANAGEMENT INSTITUTE (PMI). O padrão de gerenciamento de projetos e Guia do conhecimento em gerenciamento de projetos (Guia PMBOK). 7. ed. Newtown Square: PMI, 2021.

### Nota de consolidação

Alterações feitas pela Coordenação nos textos originais:

- Foram usadas as partes principais de cada pesquisa, com o texto original. Ficaram de fora trechos de apoio

que se repetem entre os documentos e as referências individuais, reunidas na lista acima.

- Gustavo: os rótulos “Risco 1 a 5” das respostas foram trocados pelos IDs R02, R03, R01, R04 e R05, para

casar com o registro de riscos.

- José: a base é a segunda versão enviada (PDF 2). Da primeira versão entraram a referência ao PMBOK 7ª

edição e o ponto sobre o conhecimento técnico dos demais integrantes, e a lista de conceitos foi reduzida a seis itens.

- Nicolas: as colunas “Canal / Formato” e “Frequência / Quando” do plano de comunicação foram unidas em

“Canal e frequência”, para a tabela caber na página.

- Hugo: a linguagem foi ajustada ao registro dos demais textos (“pra” por “para”, “dá pra recuperar” por “é

recuperável”, “conta minha” por “cálculo próprio”). A dúvida sobre a semana e a meta de treinamento passou a remeter às premissas da Seção 7. A referência vaga ao PMBOK foi substituída pelas edições listadas.

- Vinícius: mantido sem alteração de conteúdo. Apenas a numeração das seções foi adaptada a este

documento.

- Os valores da Seção 6 são somas da Coordenação e precisam ser validados pela equipe na oficina.

Equipe 2 (Karzones) – P2 Sistema Acadêmico 360 | Pesquisa Central – Unidade 3 | v0.1 Página 12
