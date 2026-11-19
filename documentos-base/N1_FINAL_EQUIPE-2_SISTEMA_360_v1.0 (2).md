<!-- Convertido de: documentos-base/N1_FINAL_EQUIPE-2_SISTEMA_360_v1.0 (2).pdf -->

<!-- página 1 -->

# 📖

# Católica SC

Centro Universitário

## N1-FINAL - Dossiê de Iniciação do Projeto

Gestão de Projetos | Consolidação da Unidade 1

**Identificação**

| Equipe: | Equipe 2 (Karzones) | Projeto: | Sistema Acadêmico 360 |
| --- | --- | --- | --- |
| Integrantes: | Gustavo, Nicolas Nass, José Joenk, Vinicius Gilgen, Luan Nick, Hugo | Data / Versão: | 23/09/2026 - v1.0 |

1. Fundamentos e contexto do projeto

**1.1 Identificação e descrição resumida do projeto**

Sistema Acadêmico 360: Consiste na implantação de um sistema unitário (único) focado em englobar e unificar todos os setores de uma instituição de ensino (alunos, professores, diretoria, financeiro e demais funcionários).

**1.2 Problema ou oportunidade**

A instituição opera com sistemas legados separados por setores, resultando em excesso de processos manuais (como emissão de procedimentos e documentos) e ausência de integração automatizada entre as áreas.

**1.3 Justificativa**

O projeto justifica-se pela precisão do cliente em modernizar e unificar seus setores, necessitando de uma automação que elimine o trabalho manual, ofereça alta capacidade de integração, opere em uma interface moderna e intuitiva, e garanta a migração de dados sem perdas.

**1.4 Objetivo geral e objetivos específicos**

- Objetivo geral: Implantar um sistema unitário que vai englobar todos os setores da instituição.

- Objetivos específicos:

1. Executar o planejamento e a documentação do projeto.

2. Aprovar e executar o processo de migração de 100% dos dados históricos.

3. Concluir as implementações das áreas e setores da instituição (alunos, professores, diretor, financeiro).

**1.5 Benefícios esperados**

União de todos os setores em um mesmo ambiente, redução significativa do trabalho manual por meio de templates, maior agilidade no rendimento profissional e modernização da arquitetura de dados da instituição.

**1.6 Critérios de sucesso**

- Redução de pelo menos 80% no tempo gasto pela secretaria acadêmica na emissão de documentos, comprovado

via teste cronometrado antes e depois da implementação.

- Migração de 100% dos dados históricos de alunos, notas e financeiro para o novo sistema sem corrupção de

registros, comprovado via "teste de contagem" entre os bancos de dados.

2. Abordagem de gerenciamento

**2.1 Abordagem escolhida**

Híbrida: Planejamento → Desenvolvimento iterativo → Validação com usuários → Migração e transição.

<!-- página 2 -->

**2.2 Justificativa da abordagem**

A necessidade de acautelar dados sensíveis e garantir que não haja perda no processo de migração caracteriza-se como preditiva (controle formal e EAP). Em contrapartida, a produção dos módulos do sistema, o design de interface e a adequação às necessidades dos usuários exigem validação constante, adequando-se à metodologia ágil (backlog iterativo).

3. Termo de Abertura

| Campo | Preenchimento |
| --- | --- |
| Entregas principais | Módulos de cada setor desenvolvidos, testados e validados iterativamente; Processo completo de migração de dados finalizado. |
| Premissas | A equipe da instituição adotará o sistema único de forma integral, de modo que todas as necessidades setoriais mapeadas e funcionalidades sejam igualmente atendidas. |
| Restrições | O sistema legado não pode ficar fora do ar em nenhum instante antes da migração oficial. As manutenções e transições devem ocorrer fora do horário de expediente. |
| Patrocinador | Direção escolar municipal. |
| Autoridade de decisão | O Gerente (Vinicius) e a equipe tomam as decisões operacionais do projeto. O Patrocinador é a autoridade que aprova mudanças de escopo e orçamento. |

4. Stakeholders e governança

**4.1 Principais stakeholders**

- Direção escolar municipal: Patrocinador.

- Secretaria acadêmica: Cliente / Usuário final.

- Coordenação do curso e Professores: Usuários.

- Estudantes: Usuários.

- Setor Financeiro e Setor Jurídico (Conformidade): Usuários / Consultados.

- Equipe de tecnologia: Equipe / Manutenção.

**4.2 Matriz de poder e interesse**

- Alto Poder / Alto Interesse: Direção escolar municipal (Patrocinador). Justificativa: Financiam e aprovam mudanças

de escopo, esperando unificação total.

- Baixo Poder / Alto Interesse: Secretaria acadêmica, Professores e Estudantes. Justificativa: Usarão o sistema

diariamente e são os maiores interessados na redução do trabalho manual e acesso facilitado.

- Alto Poder / Baixo Interesse: Setor jurídico e de conformidade. Justificativa: Não gerenciam a operação diária, mas

podem barrar o projeto caso a documentação legislativa não seja devidamente fornecida.

- Baixo Poder / Baixo Interesse: Equipe de tecnologia base. Justificativa: Participarão apenas do treinamento e do

período de transição.

**4.3 Governança inicial**

O Patrocinador atua como aprovador primário para qualquer mudança de escopo ou orçamento. A secretaria acadêmica e os docentes operam como consultados durante a validação dos módulos iterativos. Casos severos envolvendo a integridade do banco de dados legado devem ser escalonados.

5. Escopo e requisitos

**5.1 Declaração inicial de escopo**

O projeto entrega a unificação completa dos cadastros e acessos da instituição, englobando lançamento de notas, frequência, integração com cobranças financeiras, emissão automatizada de documentos e a migração de 100% dos dados históricos sem corrupção.

<!-- página 3 -->

**5.2 Principais requisitos**

1. Requisito: O sistema deve automatizar a emissão de documentos por meio de templates. Aceite: Teste

cronometrado com redução de 80% do tempo gasto.

2. Requisito: O sistema deve migrar os dados históricos completos (alunos, notas, financeiro). Aceite: Teste de

contagem confirmando 100% de transferência sem perdas.

3. Requisito: O sistema deve permitir o lançamento de notas e frequência escolar. Aceite: A nota lançada pelo

professor reflete instantaneamente na interface do estudante.

**5.3 Limites e exclusões**

Estão explicitamente excluídos o fornecimento e a manutenção de hardware/computadores para a escola, bem como a migração de sistemas paralelos que não possuam relação com o escopo acadêmico ou financeiro.

6. Decomposição do trabalho

**O projeto utiliza uma Estrutura Híbrida (EAP + Backlog):**

**EAP (Parte Preditiva):**

- 1. Processo de Migração

- 1.1. Extração de Dados

- Pacote: Migração do histórico (Critério: Teste de contagem de referências a 100%).

- 2. Transição

- 2.1. Treinamento

- Pacote: Treinar equipe de tecnologia e funcionários (Critério: Lista de presença assinada e usuários capazes

de logar).

**Backlog (Parte Ágil):**

- Épico: Módulo Secretaria

- Item: Automação e templates para emissão de documentos acadêmicos (Alta Prioridade). Critério: Documento

emitido em -80% do tempo.

- Épico: Módulo Docente

- Item: Tela para lançamento de notas e acompanhamento de frequência (Alta Prioridade). Critério: Dados salvos e

visíveis aos alunos.

7. Estimativas preliminares

| Pacote / item | Tam. | Esforço | Duração | Premissa / incerteza |
| --- | --- | --- | --- | --- |
| Migração do histórico | A est. | A est. | A est. | Incerteza: O comportamento exato e a estrutura técnica do banco de dados atual (sistema legado) ainda não são totalmente conhecidos. |
| Automação e templates (Secretaria) | A est. | A est. | A est. | Incerteza: As regras de negócio específicas e legislações vigentes quanto à emissão documental não foram 100% detalhadas pela instituição. |
| Treinar equipe e funcionários | A est. | A est. | A est. | Premissa: A equipe da instituição estará engajada para adoção integral. |

8. Registro de responsabilidades

| Integrante | Principais contribuições ao longo da unidade |
| --- | --- |

<!-- página 4 -->

| Luan Nick | Construção da análise inicial do projeto, estruturação geral e preenchimento da decomposição final (EAP/Backlog). |
| --- | --- |
| Vinicius Gilgen | Definição técnica e justificativa da abordagem híbrida, além da documentação primária do termo de abertura. |
| Nicolas Nass | Contribuição volumétrica no brainstorm, definição técnica das exclusões de escopo e identificação de dependências externas. |
| Gustavo / José / Hugo | Condução de ideias durante o termo de abertura, levantamento de restrições operacionais e alinhamento de requisitos de transição. |

9. Checklist de coerência

| Verificação | Coerente? |
| --- | --- |
| As entregas do Termo de Abertura (Seção 3) aparecem no escopo (Seção 5) | [X] sim |
| Os aprovadores da governança (4.3) aparecem no mapeamento de stakeholders (4.1) | [X] sim |
| Toda entrega do escopo (Seção 5) está representada na EAP/backlog (Seção 6) | [X] sim |
| A EAP/backlog e as estimativas (Seções 6 e 7) são coerentes com a abordagem (Seção 2) | [X] sim |
| As premissas de estimativa (Seção 7) não contradizem as do Termo de Abertura (Seção 3) | [X] sim |
| A decisão preliminar da Aula 2 (manter/reduzir/dividir/reavaliar) ainda se sustenta | [X] sim |
