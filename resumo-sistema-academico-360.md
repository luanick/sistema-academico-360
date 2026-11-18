# Sistema Acadêmico 360 — dados coletados

Fonte: pasta ProjetoSistemaAcademico/General (Gestão de Projetos, Professor da disciplina, Católica SC).

## Identificação
- Projeto P2 "Sistema Acadêmico 360"; natureza: substituição e migração de sistema legado.
- Equipe 2 / "Karzones" (também chamada Equipe B no edital).
- Integrantes: Luan Nick, Vinícius Gilgen (gerente), Nicolas Nass, José Joenk, Gustavo, Hugo.
- Patrocinador: Direção escolar municipal (aprova mudanças de escopo e orçamento).

## Problema e objetivo
- Problema: sistemas legados separados por setor, muito trabalho manual, sem integração.
- Objetivo geral: implantar um sistema único que englobe todos os setores (alunos, professores, direção, financeiro, demais funcionários).
- Benefícios: setores unificados, menos trabalho manual (templates de documentos), interface moderna, alta integração.

## Critérios de sucesso
- Reduzir em ≥80% o tempo da secretaria na emissão de documentos (teste cronometrado antes/depois).
- Migrar 100% dos dados históricos (alunos, notas, financeiro) sem corrupção (teste de contagem entre bancos).

## Abordagem
- Híbrida: planejamento → desenvolvimento iterativo → validação com usuários → migração e transição.
- Preditivo (EAP): migração, transição, treinamento. Ágil (backlog): módulos de secretaria, docente, interface.
- Decisão da Aula 2: Manter. Matriz: proposto 14, solução menor 12, não fazer 12.

## Escopo
- Incluído: cadastro, matrículas, notas e frequência, históricos, documentos, integração financeira, migração/validação, testes, transição, convivência com legado, implantação controlada.
- Excluído: desenvolver sistema do zero (se usar plataforma pronta), trocar todos os sistemas administrativos, hardware, mudanças financeiras além da integração, manutenção permanente pós-projeto.
- 8 requisitos de alto nível (cadastro, matrícula, notas/frequência, histórico, documentos, integração financeira, migração, continuidade na transição).

## Restrições, premissas, riscos
- Restrição: legado não pode ficar fora do ar antes da migração; manutenção/transição fora do expediente; dados não podem ser perdidos; documentos mantêm validade.
- Premissa: equipe da instituição adotará o sistema integralmente; dados do legado acessíveis.
- Riscos: estrutura do banco legado desconhecida; regras de negócio (financeiro, avaliação, documentos) desconhecidas; prazo/custo do cliente indefinidos.
- Eventos Unidade 3 (edital): 18% dos cadastros históricos duplicados/inconsistentes; analista de BD deslocado por 3 semanas; secretaria reclama de priorizar financeiro; nova exigência de histórico digital com assinatura eletrônica; 85% dos registros validados, migração piloto atrasou 10 dias, treinamento em 45% dos usuários.

## Stakeholders
- Direção (alto poder/alto interesse); Secretaria, professores, estudantes (baixo poder/alto interesse); Jurídico/conformidade (alto poder/baixo interesse); Financeiro; Coordenação; Equipe de TI; fornecedor do legado (dependência externa).

## Cronograma (Unidade 2)
- 28 semanas, 17 atividades (A1–E4), caminho crítico sem folga: A1,A2,A3,B1,B2,B3,D1,D2,D3,E1–E4.
- Marcos: semana 7 escopo aprovado; 14 dados migrados e validados; 21 plataforma validada; 28 operação inicial concluída.
- 3 releases, 8 sprints de 3,5 semanas.

## Recursos e custo
- Equipe: gerente 50%, 2 desenvolvedores, analista de BD, analista de testes, especialista de infraestrutura 30%; representantes do cliente 20%. 3.288 h pagas.
- Orçamento: pessoas R$ 169.560 + fornecedores R$ 255.000 (licença 140.000, consultoria de migração 85.000, treinamento 30.000) = R$ 424.560.
- + contingência R$ 30.000 + reserva gerencial (5%) R$ 22.728 = R$ 477.288. Teto R$ 480.000; folga R$ 2.712.
- Plano se teto cair 10% (R$ 432.000): cortes somam R$ 45.464, orçamento R$ 431.824.
- Conflito principal: 4 configurações (13 sem) para 2 desenvolvedores (14 sem), resolvido pareando.

## Lacunas
- Estimativas de tamanho/esforço/duração do N1-FINAL estão "A est.".
- Plataforma/fornecedor da nova solução ainda indefinidos.
- Pacote de planejamento da N2 não localizado (marcos e alocações são premissas).
