<!-- Convertido de: documentos-base/N1_CP06-07_EQUIPE-B_SISTEMA-ACADEMICO-360_v0.1 (1).pdf -->

<!-- página 1 -->

## Gestão de Projetos

## N1-cp06/07 – Definição e decomposição inicial do projeto

### Equipe B

### Projeto: Sistema Acadêmico 360

### Integrantes: Gustavo Henrique de Morais, José Manoel Joenk,

### Luan Nick Ferreira da Silva, Nicolas Nass, Vinícius Henrique Gilgen

### da Silva

### Data: 10/09/2026 – v0.1

### Início

| Stakeholder Relevante | Expectativa ou Decisão Relevante | Implicação para o Escopo |
| --- | --- | --- |
| Direção | Espera uma substituição segura do sistema legado, com continuidade das atividades acadêmicas | Inclui implantação, transição, acompanhamento e indicadores; aprovação das principais etapas |
| Secretaria acadêmica | Necessita que cadastros, matrículas, históricos e documentos funcionem adequadamente | Esses processos devem fazer parte do escopo e ser validados antes da entrada em produção |
| Coordenações de curso | Esperam acesso adequado às informações acadêmicas e continuidade das rotinas dos cursos | Requisitos relacionados a consultas, acompanhamento acadêmico e acesso às informações devem ser considerados |
| Professores | Precisam lançar e consultar notas e frequência sem interrupções | Funcionalidades acadêmicas e validação de uso pelos professores devem fazer parte do escopo |
| Estudantes | Esperam acesso às informações acadêmicas e continuidade durante a transição | O sistema deve preservar o acesso às informações e a continuidade dos serviços |
| Setor financeiro | Necessita integração entre processos acadêmicos e financeiros | A integração com processos financeiros entra no escopo, enquanto detalhes técnicos dependem de levantamento |
| Equipe de tecnologia | Precisa garantir integração, migração, segurança e funcionamento da nova solução | Inclui migração, validação, integração, implantação e suporte à transição |
| Jurídico/Conformidade | Precisa garantir que dados e documentos mantenham sua validade e sejam tratados adequadamente | Requisitos de conformidade, preservação dos documentos e proteção |

<!-- página 2 -->

|  |  | dos dados devem ser considerados |
| --- | --- | --- |
| Fornecedor do sistema atual | Pode ser necessário para acesso, exportação ou esclarecimento sobre dados do sistema legado | Torna-se uma dependência externa para determinadas atividades de migração e transição |

### Produto, Entregas, Inclusões e Exclusões

| Elemento | Descrição |
| --- | --- |
| Produto/Resultado | Nova plataforma acadêmica implantada, com migração e validação dos dados históricos e transição segura do sistema legado, mantendo a continuidade das atividades acadêmicas |
| Entregas principais | Levantamento e definição dos requisitos acadêmicos; Seleção/configuração da nova plataforma acadêmica; Preparação e migração dos dados históricos; Integração com processos financeiros; Testes e validação da nova plataforma; Implantação e transição entre sistemas; Acompanhamento da operação inicial |
| Incluído no escopo | Cadastro acadêmico; Matrículas; Lançamento e consulta de notas; Registro e consulta de frequência; Históricos acadêmicos; Emissão/gestão de documentos acadêmicos; Integração com processos financeiros; Levantamento, tratamento, migração e validação dos dados históricos; Testes da nova plataforma; Planejamento e execução da transição; Período de convivência entre sistema antigo e novo, quando necessário; Validação da continuidade operacional; Implantação controlada |
| Excluído no escopo | Desenvolvimento de um sistema acadêmico completamente novo do zero, caso seja utilizada uma plataforma existente; Substituição imediata de todos os sistemas administrativos da instituição; Alteração dos processos financeiros que não sejam necessários à integração acadêmico-financeira; Digitalização de documentos físicos que não estejam relacionados aos dados necessários para a migração; Manutenção permanente do sistema após o encerramento do projeto; Mudanças organizacionais não relacionadas à implantação do novo sistema |
| Dependências Externas: | Disponibilidade e qualidade dos dados do sistema legado; Acesso às informações e mecanismos de exportação do sistema atual; Participação do fornecedor do sistema legado, quando necessária; Disponibilidade do fornecedor da nova solução; Sistemas e responsáveis pelo processo financeiro; Disponibilidade dos usuários-chave para validação e testes; Aprovação da direção e demais responsáveis pelas áreas |

### Requisitos de alto nível

| # | Requisito de alto nível |
| --- | --- |
| 1 | O sistema deve permitir o cadastro e a atualização das informações acadêmicas dos estudantes |
| 2 | O sistema deve permitir realizar e consultar matrículas dos estudantes |
| 3 | O sistema deve permitir o lançamento e a consulta de notas e frequência |
| 4 | O sistema deve permitir consultar e preservar históricos acadêmicos |

<!-- página 3 -->

| 5 | O sistema deve permitir gerar e consultar documentos acadêmicos necessários à instituição |
| --- | --- |
| 6 | O sistema deve possibilitar a integração com os processos financeiros relacionados às atividades acadêmicas |
| 7 | O projeto deve permitir a migração dos dados históricos do sistema legado para a nova plataforma |
| 8 | A implantação deve permitir a continuidade das atividades acadêmicas durante a transição do sistema antigo para o novo |

### Critérios de aceite

| Requisito/entrega | Critério de aceite verificável |
| --- | --- |
| Cadastro acadêmico | Deve ser possível cadastrar, consultar e atualizar estudantes em ambiente de teste, sem perda dos dados registrados |
| Documentos acadêmicos | Os documentos definidos no escopo devem ser gerados/consultados na nova plataforma e validados pelo responsável acadêmico |
| Migração | Os dados históricos selecionados devem ser transferidos para a nova plataforma e submetidos a conferência e validação |

### Premissas e Restrições de Escopo

| Premissas Assumidas | Restrições Conhecidas |
| --- | --- |
| A instituição disponibilizará representantes das áreas para validação dos requisitos | Os dados históricos não podem ser perdidos |
| Será possível obter os dados necessários do sistema legado para a migração | Os documentos emitidos precisam manter sua validade |
| A implantação poderá ocorrer de forma controlada | A instituição não pode interromper as atividades acadêmicas |
| A nova solução terá condições de atender aos requisitos definidos | Períodos de matrícula e fechamento acadêmico são críticos |
| Os responsáveis pelos sistemas envolvidos colaborarão com as integrações necessárias | Poderá ser necessário manter os dois sistemas em funcionamento durante parte da transição |
| Será possível estabelecer uma estratégia de transição entre os sistemas | Diferentes setores possuem rotinas e prioridades próprias |

### Questões ainda em aberto e fontes de mudança futura

| Questões ainda em aberto | Possíveis fontes de mudança futura |
| --- | --- |
| Qual é a qualidade real dos dados históricos? | Necessidade de limpeza ou tratamento adicional dos dados |
| Quais dados históricos deverão obrigatoriamente ser migrados? | Alteração dos requisitos de migração |
| Qual será a nova plataforma utilizada? | Escolha ou mudança do fornecedor da solução |
| Quais integrações financeiras serão necessárias? | Mudanças nos sistemas ou processos financeiros |
| Quanto tempo será necessário manter os dois sistemas em paralelo? | Resultados dos testes e da implantação controlada |

<!-- página 4 -->

| Quais perfis de acesso serão necessários? | Identificação de novos grupos de usuários ou requisitos de segurança |
| --- | --- |
| Quais períodos são mais adequados para a implantação? | Alterações no calendário acadêmico |
| Quais documentos precisam ter prioridade na migração/validação? | Necessidades identificadas pela secretaria e pelas coordenações |

### Definição e divisão do trabalho

Abordagem de gerenciamento: Preditiva com elementos de Híbrida Entregas principais do Escopo: Levantamento e definição dos requisitos acadêmicos; Seleção/configuração da nova plataforma acadêmica; Preparação e migração dos dados históricos; Integração com processos financeiros; Testes e validação da nova plataforma; Implantação e transição entre sistemas; Acompanhamento da operação inicial

### Escolha do Artefato

EAP Predominante Híbrido (EAP + Backlog) Não sei fazer a caixinha marcada no word

### EAP

| Entrega Principal | Subentrega | Pacote de Trabalho | Critério de Conclusão |
| --- | --- | --- | --- |
| Planejamento e Requisitos | Levantamento | Levantar requisitos acadêmicos | Requisitos levantados e validados pelos responsáveis das áreas |
|  | Levantamento | Identificar perfis de usuários | Perfis de usuários identificados e documentados |
|  | Validação | Validar requisitos | Requisitos aprovados pelos responsáveis definidos |
| Nova Plataforma Acadêmica | Configuração | Configurar cadastro acadêmico | Cadastro disponível e validado em ambiente de teste |
|  | Configuração | Configurar matrículas | Processo de matrícula validado em ambiente de teste |
|  | Configuração | Configurar notas e frequência | Lançamento e consulta validados pelos usuários responsáveis |
|  | Documentos | Configurar histórico e documentos | Documentos definidos no escopo validados |
| Migração de Dados | Preparação | Levantar dados históricos | Conjunto de dados para migração identificado |
|  | Preparação | Preparar dados | Dados preparados conforme regras de migração definidas |
|  | Migração | Executar migração | Dados selecionados transferidos para a nova plataforma |
|  | Migração | Validar dados migrados | Responsáveis validam os dados migrados e registram os resultados |
| Integrações | Financeiro | Levantar requisitos de integração | Fluxos de integração definidos e aprovados |

<!-- página 5 -->

|  | Financeiro | Implementar / configurar integração | Integração executada e validada em ambiente de teste |
| --- | --- | --- | --- |
| Testes e Validação | Testes | Executar testes funcionais | Requisitos definidos são testados e resultados registrados |
|  | Testes | Executar testes de integração | Integrações testadas e resultados registrados |
|  | Validação | Validar com usuários chave | Usuários-chave aprovam os processos definidos para implantação |
| Transição e Implantação | Preparação | Elaborar plano de transição | Plano de transição aprovado pelos responsáveis |
|  | Preparação | Preparar convivência entre sistemas | Estratégia de utilização dos sistemas definida e testada |
|  | Implantação | Realizar implantação controlada | Nova plataforma disponibilizada no ambiente definido sem interrupção não planejada |
| Operação Inicial | Acompanham ento | Monitorar utilização inicial | Problemas da operação inicial registrados e acompanhados |
|  | Acompanham ento | Corrigir problemas prioritários | Problemas críticos identificados na implantação recebem tratamento conforme critérios definidos |

### Backlog – Elementos Híbridos

| Épico | Funcionalidade / Item | Prioridade | Critério de Conclusão |
| --- | --- | --- | --- |
| Gestão acadêmica | Cadastro e atualização de estudantes | Alta | Cadastro testado e validado pelos usuários responsáveis |
| Gestão acadêmica | Consulta e realização de matrícula | Alta | Fluxo de matrícula validado em ambiente de teste |
| Gestão acadêmica | Lançamento de notas e frequência | Alta | Professores/usuários definidos conseguem executar e validar o processo |
| Dados históricos | Consulta de histórico migrado | Alta | Dados migrados são conferidos e aprovados pela secretaria |
| Documentos | Consulta/emissão de documentos acadêmicos | Média | Documentos definidos no escopo são validados |
| Integração | Integração com processo financeiro | Alta | Fluxo de integração testado e aprovado pelos setores envolvidos |

### Como os dois artefatos se relacionam

A EAP cobre as entregas estruturais e mais estáveis do projeto, como planejamento, migração, integração, testes, treinamento e transição. O backlog complementa a EAP nas funcionalidades que precisam de validação incremental com usuários,

<!-- página 6 -->

permitindo registrar itens, prioridades, critérios de conclusão e ajustes decorrentes dos testes.

EAP cuidaria por exemplo da migração e validação dos dados históricos e da nova plataforma acadêmica, enquanto Backlog ficaria com a validação da consulta dos históricos migrados pelos usuários da secretaria e com cadastro, matrícula, notas e frequência, com validação incremental pelos usuários.

### Cobertura do Escopo

| Entrega do Escopo | Onde aparece na decomposição |
| --- | --- |
| Levantamento e definição dos requisitos | EAP – Planejamento e requisitos |
| Nova plataforma acadêmica | EAP – Nova plataforma acadêmica |
| Cadastro acadêmico | EAP – Configuração / Backlog – Gestão acadêmica |
| Matrículas | EAP – Configuração / Backlog – Gestão acadêmica |
| Notas e frequência | EAP – Configuração / Backlog – Gestão acadêmica |
| Históricos e documentos | EAP – Documentos / Backlog – Dados históricos |
| Migração de dados | EAP – Migração de dados |
| Validação dos dados | EAP – Migração |
| Integração financeira | EAP – Integrações / Backlog – Integração |
| Testes | EAP – Testes e validação |
| Transição entre sistemas | EAP – Transição e implantação |
| Continuidade operacional | EAP – Implantação |
| Acompanhamento inicial | EAP – Operação inicial |

### Itens ainda pouco compreendidos ou incertos

| Item da decomposição | O que ainda falta esclarecer |
| --- | --- |
| Migração de dados | Qual é a qualidade dos dados históricos e qual percentual/conjunto deverá ser migrado |
| Integração financeira | Quais sistemas e informações precisam efetivamente ser integrados |
| Nova plataforma | Qual solução/fornecedor será utilizado e quais capacidades estarão disponíveis |
| Transição | Por quanto tempo os sistemas antigo e novo precisarão funcionar simultaneamente |
| Documentos acadêmicos | Quais documentos possuem prioridade e quais regras precisam ser preservadas |

<!-- página 7 -->

### Registro das contribuições

| Aluno | Contribuição |
| --- | --- |
| Gustavo | Pesquisa e ajuda com brainstorm |
| José | Ajuda com brainstorm e montagem do documento |
| Luan | Coordenação e ajuda com o brainstorm |
| Nicolas | Pesquisa e ajuda com o brainstorm |
| Vinicius | Coordenação e ajuda com o brainstorm |
