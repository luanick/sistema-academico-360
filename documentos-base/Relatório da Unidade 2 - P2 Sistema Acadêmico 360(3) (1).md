<!-- Convertido de: documentos-base/Relatório da Unidade 2 - P2 Sistema Acadêmico 360(3) (1).pdf -->

<!-- página 1 -->

Relatório da Unidade 2 - P2 Sistema Acadêmico 360

| Relatório da Unidade 2 - P2 Sistema Acadêmico 360 Oct 26, 2026 · @Luan nick Resumo O P2 cabe nas 28 semanas e no teto de R$ 480.000: o orçamento proposto é de R$ 477.288, R$ 2.712 abaixo do teto. Cronograma: os 56 dias da Aula 11 viram 28 semanas (1 dia = 0,5 semana), com as mesmas 17 atividades, dependências e caminho crítico. Entrega: 3 releases e 8 sprints de 3,5 semanas, com marcos nas semanas 7, 14, 21 e 28. Custo: R$ 169.560 de pessoas + R$ 255.000 de fornecedores = R$ 424.560, mais R$ 30.000 de contingência (riscos identificados) e R$ 22.728 de reserva gerencial (5%). Ponto a validar: não localizamos o pacote de planejamento da N2. Os marcos mínimos e as alocações por período são premissas nossas (seção 10). 1. Atividades, dependências e cronograma O caminho crítico (A1, A2, A3, B1, B2, B3, D1, D2, D3, E1 a E4) soma 28 semanas e não tem folga; as quatro configurações do bloco C têm de 3 a 4,5 semanas de folga. Convertemos cada dia da Aula 11 em meia semana (1 dia = 0,5 semana); a ordem e as dependências não mudam. Rede de atividades do P2 (durações em dias, da Aula 11). |  |  |  |  |  |  |
| --- | --- | --- | --- | --- | --- | --- |
| ID | Atividade | Predecessoras | Duração (sem) | Início (sem) | Fim (sem) | Folga (sem) |
| A1 | Levantamento | - | 2 | 0 | 2 | 0 |
| A2 | Perfis | A1 | 2,5 | 2 | 4,5 | 0 |
| A3 | Validar requisitos | A2 | 2,5 | 4,5 | 7 | 0 |
| B1 | Preparar dados | A3 | 2 | 7 | 9 | 0 |
| B2 | Migrar | B1 | 3 | 9 | 12 | 0 |

Page 1 of 14

<!-- página 2 -->

Relatório da Unidade 2 - P2 Sistema Acadêmico 360

| ID | Atividade | Predecessoras | Duração (sem) | Início (sem) | Fim (sem) | Folga (sem) |
| --- | --- | --- | --- | --- | --- | --- |
| B3 | Validar dados | B2 | 2 | 12 | 14 | 0 |
| C1 | Configurar cadastro | A3 | 2,5 | 7 | 9,5 | 4,5 |
| C2 | Configurar matrículas | A3 | 3 | 7 | 10 | 4 |
| C3 | Configurar notas e frequência | A3 | 4 | 7 | 11 | 3 |
| C4 | Configurar histórico e documentos | A3 | 3,5 | 7 | 10,5 | 3,5 |
| D1 | Integração financeira | B3, C1 a C4 | 2,5 | 14 | 16,5 | 0 |
| D2 | Testes | D1 | 2,5 | 16,5 | 19 | 0 |
| D3 | Validação com usuários | D2 | 2 | 19 | 21 | 0 |
| E1 | Plano de transição | D3 | 1,5 | 21 | 22,5 | 0 |
| E2 | Convivência com o legado | E1 | 2 | 22,5 | 24,5 | 0 |
| E3 | Implantação controlada | E2 | 2 | 24,5 | 26,5 | 0 |
| E4 | Operação inicial | E3 | 1,5 | 26,5 | 28 | 0 |
| Gantt em semanas · datas da tabela da seção 1 As linhas tracejadas marcam os quatro marcos, nas semanas 7, 14, 21 e 28. |  |  |  |  |  |  |

Page 2 of 14

<!-- página 3 -->

Relatório da Unidade 2 - P2 Sistema Acadêmico 360

| Cronograma gerado em Mermaid, com fases críticas e não críticas. Marcos: Escopo aprovado (semana 7), Dados migrados e validados (semana 14), Nova plataforma validada (semana 21), Operação inicial concluída (semana 28). 2. Releases e sprints Os mesmos 3 releases da Aula 12 cabem em 8 sprints de 3,5 semanas, duas por fase do cronograma. Cada sprint termina com uma revisão com o cliente (secretaria e financeiro). A capacidade de cada sprint é uma estimativa; a velocidade só será medida depois da Sprint 1. |  |  |  |  |
| --- | --- | --- | --- | --- |
| Release | Sprint | Semanas | Conteúdo da sprint | Incremento mostrado ao cliente |
| R1: base migrada e configurada | S1 | 0 a 3,5 | A1 e início de A2 | Requisitos levantados |
|  | S2 | 3,5 a 7 | Fim de A2 e A3 | Escopo aprovado (marco) |
|  | S3 | 7 a 10,5 | B1, início de B2, C1 a C4 em paralelo | Dados preparados e módulos configurados |
|  | S4 | 10,5 a 14 | Fim de B2 e B3 | Dados migrados e validados (marco) |
| R2: plataforma integrada e validada | S5 | 14 a 17,5 | D1 e início de D2 | Integração financeira funcionando |
|  | S6 | 17,5 a 21 | Fim de D2 e D3 | Nova plataforma validada (marco) |

Page 3 of 14

<!-- página 4 -->

Relatório da Unidade 2 - P2 Sistema Acadêmico 360

| Release | Sprint |  | Semanas |  | Conteúdo da sprint |  | Incremento mostrado ao cliente |  |  |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| R3: em operação, com o legado em paralelo | S7 |  | 21 a 24,5 |  | E1 e E2 |  | Plano de transição e convivência |  |  |
|  | S8 |  | 24,5 a 28 |  | E3 e E4 |  | Operação inicial concluída (marco) |  |  |
| Atividades que cruzam a fronteira de uma sprint (A2, B2, D2) continuam na seguinte; o que é mostrado ao cliente é o que estiver concluído no fim de cada sprint. 3. Recursos e alocação A equipe do projeto soma 3.288 horas pagas pelo projeto (R$ 169.560); ninguém passa de 100% em nenhuma semana. Horas = semanas × 40 × dedicação. |  |  |  |  |  |  |  |  |  |
| Papel |  | Pessoas |  | Dedicação e período |  | Horas |  | R$/h | Custo (R$) |
| Gerente de projeto |  | 1 |  | 50%, semanas 1 a 28 |  | 560 |  | 80 | 44.800 |
| Desenvolvedor |  | 2 |  | 100% nas semanas 8 a 21; 50% nas semanas 22 a 28 |  | 1.400 |  | 45 | 63.000 |
| Analista de banco de dados |  | 1 |  | 50% nas semanas 1 a 7; 100% nas 8 a 14; 50% nas 15 a 17 |  | 480 |  | 40 | 19.200 |
| Analista de testes |  | 1 |  | 50% nas semanas 8 a 14; 100% nas 15 a 21; 50% nas 22 a 28 |  | 560 |  | 40 | 22.400 |
| Especialista de infraestrutura |  | 1 |  | 30%, semanas 5 a 28 |  | 288 |  | 70 | 20.160 |
| Subtotal pago pelo projeto |  |  |  |  |  | 3.288 |  |  | 169.560 |
| Representantes da secretaria e do financeiro |  | 2 |  | 20%, semanas 1 a 28 |  | 448 |  | 0 | 0 (custo do cliente) |
| Recursos materiais e tecnológicos: Plataforma acadêmica: licença contratada (seção 4), usada da semana 8 em diante. Ambientes de migração e de homologação: montados pelo especialista de infraestrutura entre as semanas 5 e 7, antes de B1. Base do sistema legado e acesso aos dados: fornecidos pelo cliente desde a semana 1. Quadro do backlog e estações de trabalho: ferramentas já disponíveis, sem custo adicional (premissa). |  |  |  |  |  |  |  |  |  |

Page 4 of 14

<!-- página 5 -->

Relatório da Unidade 2 - P2 Sistema Acadêmico 360

| 4. Fornecedores e fazer ou contratar Contratamos três itens (R$ 255.000) e fazemos o restante com a equipe própria; a regra foi contratar o que exige capacidade que a equipe não tem ou que transfere risco. |  |  |  |  |
| --- | --- | --- | --- | --- |
| Item | Decisão | Valor (R$) | Contratação / uso | Motivo |
| Licença da plataforma | Contratar | 140.000 | Contrato na semana 7; uso da semana 8 | Produto pronto; desenvolver um sistema acadêmico do zero não cabe em 28 semanas |
| Consultoria de migração | Contratar | 85.000 | Semanas 8 a 14 (B1 a B3) | A migração é a cadeia mais longa e de maior risco; a consultoria traz experiência com dados legados |
| Treinamento | Contratar | 30.000 | Semanas 22 a 26 (E1 a E3) | Capacitação dos usuários sem tirar os desenvolvedores do projeto |
| Levantamento e perfis (A1 a A3) | Fazer | em pessoas | Semanas 1 a 7 | Exige conhecimento do negócio, ao lado dos representantes do cliente |
| Configurações (C1 a C4) | Fazer | em pessoas | Semanas 8 a 14 | Os 2 desenvolvedores já estão no pacote; terceirizar duplicaria custo |
| Integração financeira, testes e validação (D1 a D3) | Fazer | em pessoas | Semanas 15 a 21 | Teste e validação precisam do domínio do projeto |
| Transição e operação inicial (E1 a E4) | Fazer | em pessoas | Semanas 22 a 28 | Compromisso direto com o cliente |
| Os prazos de pagamento dos fornecedores são uma premissa nossa (seção 10). |  |  |  |  |

Page 5 of 14

<!-- página 6 -->

Relatório da Unidade 2 - P2 Sistema Acadêmico 360

## 5. Conflitos de recurso e resolução

O conflito real está nas semanas 8 a 14, quando as quatro configurações (13 semanas de trabalho) disputam 2 desenvolvedores (14 semanas disponíveis). Resolvemos pareando as configurações, sem atrasar D1.

Page 6 of 14

<!-- página 7 -->

Relatório da Unidade 2 - P2 Sistema Acadêmico 360

| Conflito | Semanas | Causa | Resolução | Efeito |
| --- | --- | --- | --- | --- |
| 4 configurações para 2 desenvolvedores | 8 a 14 | C1 (2,5) + C2 (3) + C3 (4) + C4 (3,5) = 13 semanas de trabalho; janela de 7 semanas × 2 = 14 | Dev 1 faz C3 e depois C1 (6,5 sem); Dev 2 faz C4 e depois C2 (6,5 sem) | Ocupação de 93%; sobra 0,5 semana por desenvolvedor (a folga de C1 a C4 absorve atrasos, sem tocar no caminho crítico). Com 1 desenvolvedor, D1 atrasaria 6 semanas |
| Migração e configurações no mesmo ambiente | 9 a 12 | B2 (migrar) e C1 a C4 usam o mesmo especialista de infraestrutura (30%) | Janelas de ambiente fixas, definidas na semana 7; mudanças de ambiente só entre sprints | Sem atraso; a migração tem prioridade por estar no caminho crítico |
| Disponibilidade dos representantes do cliente (20%) | 4,5 a 7 e 19 a 21 | A3 e D3 pedem validação intensa | Agendar as validações com 2 semanas de antecedência; se for preciso, subir para 40% nessas janelas (custo do cliente) | Sem custo para o projeto |
| Analista de testes dividido entre preparar casos e validar dados | 12 a 14 | B3 (validar dados) coincide com a preparação dos testes | 50% de dedicação: valida os dados na parte da manhã e prepara os casos à tarde | Sem atraso |
| Com 2 desenvolvedores, a margem de cada um nas configurações é de só 0,5 semana. Risco aceito: C1 a C4 têm de 3 a 4,5 semanas de folga em relação a D1, então um atraso nelas consome folga e não prazo; o analista de BD fica dedicado à migração (B1 a B3), que está no caminho crítico. Atraso maior que a folga aciona a reserva (seção 8). |  |  |  |  |

Page 7 of 14

<!-- página 8 -->

Relatório da Unidade 2 - P2 Sistema Acadêmico 360

| 6. Matriz RACI Cada linha tem exatamente um A (quem responde pelo resultado) e ao menos um R (quem executa); A/R indica que a mesma pessoa faz as duas coisas. R = executa, A = responde, C = consultado, I = informado. |  |  |  |  |  |  |  |
| --- | --- | --- | --- | --- | --- | --- | --- |
| Entrega | Gerente | Dev | Analista BD | Analista testes | Infra | Cliente (representantes) | Fornecedores |
| A1 Levantamento | A/R | I | R |  |  | C |  |
| A2 Perfis de acesso | A | C | R |  | I | C |  |
| A3 Validar requisitos (marco Escopo aprovado) | R | I | C | I |  | A |  |
| B1 Preparar dados | I |  | A/R |  | C | C | R |
| B2 Migrar dados | I | I | A/R | I | R | I | R |
| B3 Validar dados (marco Dados migrados) | A | I | R | R | I | R | C |
| C1 a C4 Configurações | A | R | C | I | C | C |  |
| D1 Integração financeira | A | R | R | I | C | C |  |
| D2 Testes | I | R | I | A/R | C | I |  |
| D3 Validação com usuários (marco Plataforma validada) | A | C | I | R | I | R | I |
| E1 Plano de transição | A/R | C | I | I | R | C | C |
| E2 e E3 Convivência e implantação | A | R | I | R | R | C | C |
| E4 Operação inicial | A | R | I | I | R | C |  |
| Treinamento dos usuários | A | I |  |  | I | C | R |
| Aprovar mudança de escopo ou uso da reserva | R |  |  |  |  | A |  |
| O gerente responde por 10 das 15 linhas, o que combina com o papel dele, mas pesa em 50% de dedicação; por isso o analista de BD e o de testes respondem pelas entregas técnicas de B1, B2 e D2. |  |  |  |  |  |  |  |

Page 8 of 14

<!-- página 9 -->

Relatório da Unidade 2 - P2 Sistema Acadêmico 360

## 7. Custos e orçamento consolidado

O custo base é de R$ 424.560 e o orçamento total, com contingência e reserva, fica em R$ 477.288, ou 99,4% do teto. Pessoas foram estimadas de baixo para cima (horas por papel e período × valor/hora da tabela do curso); fornecedores usam os valores do pacote.

| Linha | Valor (R$) | % do teto |
| --- | --- | --- |
| Pessoas (3.288 h) | 169.560 | 35,3% |
| Licença da plataforma | 140.000 | 29,2% |
| Consultoria de migração | 85.000 | 17,7% |
| Treinamento | 30.000 | 6,3% |
| Custo base | 424.560 | 88,5% |
| Contingência (riscos identificados) | 30.000 | 6,3% |
| Linha de base de custo | 454.560 | 94,7% |
| Reserva gerencial (5% da linha de base) | 22.728 | 4,7% |
| Orçamento total | 477.288 | 99,4% |
| Teto do projeto | 480.000 | 100% |
| Folga até o teto | 2.712 | 0,6% |

Page 9 of 14

<!-- página 10 -->

Relatório da Unidade 2 - P2 Sistema Acadêmico 360

Participação de cada linha no orçamento total de R$ 477.288.

Classificação do custo base: diretos R$ 379.760 (equipe técnica e fornecedores) e indiretos R$ 44.800 (gerência do projeto); fixos R$ 255.000 (os três contratos de fornecedor) e variáveis R$ 169.560 (horas, que mudam se a dedicação ou o prazo mudarem).

O desembolso se concentra no início: a Release 1 consome 71% do custo base, porque a licença e a consultoria saem nas semanas 7 a 14.

| Release | Semanas | Pessoas (R$) | Fornecedores (R$) | Total (R$) |
| --- | --- | --- | --- | --- |
| R1 | 1 a 14 | 78.400 | 225.000 | 303.400 |
| R2 | 15 a 21 | 55.880 | 0 | 55.880 |
| R3 | 22 a 28 | 35.280 | 30.000 | 65.280 |
| Total |  | 169.560 | 255.000 | 424.560 |

Page 10 of 14

<!-- página 11 -->

Relatório da Unidade 2 - P2 Sistema Acadêmico 360

| 8. Contingência, reserva gerencial e linha de base Separamos os dois colchões: a contingência (R$ 30.000) cobre riscos que já identificamos e entra na linha de base; a reserva gerencial (R$ 22.728) cobre o que ainda não conhecemos e fica fora dela. |  |  |
| --- | --- | --- |
| Risco identificado | Se acontecer | Contingência (R$) |
| Qualidade ruim dos dados do sistema antigo | Retrabalho em B1 e B2: 2 semanas de analista de BD, 2 desenvolvedores e 50% do gerente | 13.600 |
| Consultoria precisa de mais horas que o contratado | Cerca de 11% sobre os R$ 85.000 | 9.600 |
| Retrabalho em testes e validação com usuários | 1 semana de analista de testes, 2 desenvolvedores e 50% do gerente em D2 e D3 | 6.800 |
| Total |  | 30.000 |
| Regras de uso: Contingência: só é gasta quando o risco da tabela ocorre; o gerente registra o uso e o motivo na revisão da sprint. Reserva gerencial: 5% da linha de base; o gerente propõe o uso e o cliente aprova (linha final da matriz RACI). Linha de base de custo: R$ 454.560 (custo base + contingência), usada para comparar previsto e realizado a cada sprint. Acima da reserva: qualquer necessidade além dos R$ 22.728 vira pedido de mudança, porque o teto de R$ 480.000 não muda sem acordo com o cliente. 9. Riscos de custo e alternativa se o orçamento for reduzido O maior risco de custo é a folga de apenas R$ 2.712 até o teto: uma semana de atraso no caminho crítico custa de R$ 5.040 a R$ 8.440 em pessoas, e a reserva gerencial cobre cerca de 2,7 semanas do ritmo mais caro (R$ 8.440 por semana, semanas 8 a 17). |  |  |

Page 11 of 14

<!-- página 12 -->

Relatório da Unidade 2 - P2 Sistema Acadêmico 360

| Risco de custo |  | Gatilho |  |  | Resposta |
| --- | --- | --- | --- | --- | --- |
| Atraso no caminho crítico |  | Sprint termina com item de B, D ou E sem concluir |  |  | Usar a contingência do risco correspondente; replanejar a próxima sprint na revisão |
| Pedidos novos do cliente nas revisões |  | Item entra no backlog sem sair outro |  |  | Priorizar por MoSCoW; trocar por item de mesmo tamanho ou abrir pedido de mudança |
| Validações atrasadas por falta dos representantes |  | Validação de A3 ou D3 sem data marcada 2 semanas antes |  |  | Agenda fixa; equipe parada é custo pago pelo projeto |
| Fornecedor cobra além do contrato |  | Consultoria passa de 90% das horas antes do fim de B2 |  |  | Contratos de valor fechado; excesso sai da contingência (R$ 9.600) |
| Valor/hora ou dedicação acima do previsto |  | Realizado de pessoas acima de 5% do previsto na revisão |  |  | Rever alocação; a folga de 0,6% não absorve aumento estrutural |
| Se o teto cair 10% (para R$ 432.000), precisamos cortar R$ 45.288 do orçamento de R$ 477.288. Cortamos nesta ordem, da menor para a maior perda: |  |  |  |  |  |
| Ordem | Medida |  | Economia (R$) | Impacto |  |
| 1 | Reserva gerencial de 5% para 2,5% |  | 11.364 | Menos proteção contra imprevistos |  |
| 2 | Treinamento só de multiplicadores, com material gravado |  | 15.000 | Usuários finais treinados em cascata |  |
| 3 | Analista de testes em 25% nas semanas 22 a 28 |  | 2.800 | Menos regressão durante a convivência |  |
| 4 | Adiar C4 (histórico e documentos) para depois da operação inicial |  | 6.300 | Secretaria consulta o legado para histórico até a entrega; exige acordo do cliente |  |
| 5 | Reduzir em cerca de 12% as horas da consultoria de migração |  | 10.000 | Menos acompanhamento em B3 |  |

Page 12 of 14

<!-- página 13 -->

Relatório da Unidade 2 - P2 Sistema Acadêmico 360

| Ordem | Medida | Economia (R$) | Impacto |
| --- | --- | --- | --- |
|  | Total | 45.464 | Orçamento final R$ 431.824, R$ 176 abaixo do novo teto |
| Não cortamos o caminho crítico, a licença, o núcleo da migração nem os marcos. O corte precisa ser decidido até a semana 7: depois da Release 1 restam apenas R$ 121.160 de custo base ainda não gasto, e as medidas 2 a 5 ficam menores ou impossíveis. 10. Premissas e restrições Premissas (o que adotamos sem confirmação; cada uma muda números se for diferente): Conversão de prazo: 1 dia da Aula 11 = 0,5 semana; semana de 40 horas. Marcos: o pacote de planejamento da N2 não foi localizado; adotamos Escopo aprovado (semana 7), Dados migrados (14), Nova plataforma validada (21) e Operação inicial (28). Alocação por período: o pacote fixa só os percentuais (gerente 50%, infraestrutura 30%, representantes 20%, demais em tempo integral); os períodos da seção 3 são proposta nossa. Valor/hora: gerente R$ 80, desenvolvedor R$ 45, analistas R$ 40, especialista R$ 70, cliente R$ 0. Fornecedores: valores do pacote, contratos de valor fechado e prazos de uso da seção 4. Riscos e reservas: as horas de retrabalho da contingência e o percentual de 5% da reserva são estimativas nossas. Fora do orçamento: impostos, encargos, deslocamento e ferramentas já existentes. Sprints: 3,5 semanas, com capacidade estimada; a velocidade só será conhecida após a Sprint 1. Restrições (fixas, vindas do pacote): Prazo de 28 semanas e teto de R$ 480.000. 2 desenvolvedores, gerente a 50%, especialista de infraestrutura a 30% e representantes do cliente a 20%. A migração só começa depois do escopo aprovado (A3 antes de B1) e o sistema antigo segue em paralelo até a operação inicial. |  |  |  |

Page 13 of 14

<!-- página 14 -->

Relatório da Unidade 2 - P2 Sistema Acadêmico 360

| 11. Registro das contribuições A divisão abaixo é uma proposta de responsabilidade por seção; cada integrante deve ajustar a linha dele ao que de fato fez antes da entrega. Na defesa, todos precisam dominar o relatório inteiro, pois as perguntas individuais não ficam restritas à parte de cada um. Integrante Seções sob responsabilidade (proposta) Luan Nick 1 e 2: cronograma, releases e sprints (base da Aula 11 e da Aula 12 que ele consolidou) Nicolas Nass 3 e 4: recursos, alocação, fornecedores e fazer ou contratar José Joenk 5 e 6: conflitos de recurso e matriz RACI Vinícius Gilgen 7, 8 e 9: custos, orçamento, contingência, riscos e alternativa de corte Gustavo Henrique de Morais Resumo, 10 e 11: premissas, restrições e revisão final de números 12. Registro de alterações Cada mudança feita depois da primeira versão do relatório entra aqui, com o motivo e o efeito. |  |  |  |  |
| --- | --- | --- | --- | --- |
| Data | Alteração | Motivo | Efeito | Situação |
| 26/10/2026 | Analista de banco de dados assume C1 junto com a migração (seções 3, 5 e 6) | Aumentar a folga dos 2 desenvolvedores nas configurações, de 0,5 para cerca de 1,75 semana | Sem custo extra, mas sobrecarrega o analista no caminho crítico (B1 a B3) | Desfeita no mesmo dia |
| 26/10/2026 | Volta à alocação com 2 desenvolvedores nas configurações e registro do risco de 0,5 semana de margem (seção 5) | Proteger o caminho crítico: um atraso nas configurações consome folga e não prazo | Nenhum custo novo; orçamento segue em R$ 477.288 | Em vigor |

| Integrante | Seções sob responsabilidade (proposta) |
| --- | --- |
| Luan Nick | 1 e 2: cronograma, releases e sprints (base da Aula 11 e da Aula 12 que ele consolidou) |
| Nicolas Nass | 3 e 4: recursos, alocação, fornecedores e fazer ou contratar |
| José Joenk | 5 e 6: conflitos de recurso e matriz RACI |
| Vinícius Gilgen | 7, 8 e 9: custos, orçamento, contingência, riscos e alternativa de corte |
| Gustavo Henrique de Morais | Resumo, 10 e 11: premissas, restrições e revisão final de números |

Page 14 of 14
