<!-- Convertido de: documentos-base/N2_EvidenciasIndividuais_Aula11_LUAN_NICK_v0.1 (1).pdf (o PDF é uma imagem; transcrição manual do Gantt e do diagrama de rede) -->

# Evidências individuais N2 — Aula 11 (Gantt e diagrama de rede)

- Projeto: Sistema acadêmico 360 (P2)
- Integrantes: Luan Nick, Vinicius Gilgen, Jose joenk

O PDF traz duas figuras: um diagrama de rede (atividades com duração e folga) e o Gantt "P2 - Sistema Acadêmico 360 (Gantt)". As atividades marcadas como (Crítico) no Gantt são as de folga 0 no diagrama de rede. As durações do diagrama não trazem unidade; no Gantt a folga aparece com "d" (por exemplo, "Folga 9d"). O eixo do Gantt vai de 41 a 48.

## Atividades

| Fase | Atividade | Duração | Folga | Crítica |
| --- | --- | --- | --- | --- |
| Iniciação | Levantamento de requisitos | 4 | 0 | Sim |
| Iniciação | Identificar perfis | 5 | 0 | Sim |
| Iniciação | Validar requisitos | 5 | 0 | Sim |
| Iniciação | Marco: Escopo aprovado | — | — | Marco |
| Configuração & Migração | Preparar dados históricos | 4 | 0 | Sim |
| Configuração & Migração | Configurar cadastro acadêmico | 5 | 9 | Não |
| Configuração & Migração | Configurar matrículas | 6 | 8 | Não |
| Configuração & Migração | Configurar histórico e docs | 7 | 7 | Não |
| Configuração & Migração | Configurar notas e freq. | 8 | 6 | Não |
| Configuração & Migração | Migrar dados | 6 | 0 | Sim |
| Configuração & Migração | Validar dados migrados | 4 | 0 | Sim |
| Integração | Integração financeira | 5 | 0 | Sim |
| Integração | Testes funcionais | 5 | 0 | Sim |
| Integração | Validação com usuários | 4 | 0 | Sim |
| Integração | Marco: Nova plataforma validada | — | — | Marco |
| Transição | Plano de transição | 3 | 0 | Sim |
| Transição | Preparar convivência | 4 | 0 | Sim |
| Transição | Implantação controlada | 4 | 0 | Sim |
| Transição | Operação inicial | 3 | 0 | Sim |
| Transição | Marco: Fim | — | — | Marco |

## Caminho crítico (folga 0)

Início → Levantamento de requisitos → Identificar perfis → Validar requisitos → (Escopo aprovado) → Preparar dados históricos → Migrar dados → Validar dados migrados → Integração financeira → Testes funcionais → Validação com usuários → (Nova plataforma validada) → Plano de transição → Preparar convivência → Implantação controlada → Operação inicial → Fim.

Soma das durações das atividades críticas: 56 (4+5+5+4+6+4+5+5+4+3+4+4+3).

As quatro atividades de configuração (cadastro, matrículas, histórico e docs, notas e frequência) rodam em paralelo com a sequência de preparação e migração de dados, a partir do marco "Escopo aprovado", e convergem na Integração financeira.
