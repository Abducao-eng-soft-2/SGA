# SGA

# 👽 ABUZ.AI GSA — Sistema de Gestão de Abduções

## 📌 1. Sobre o Projeto

O **ABUZ.AI GSA (Sistema de Gestão de Abduções)** é um projeto acadêmico que tem como objetivo centralizar e organizar o planejamento, a autorização, a execução e o histórico de missões de abdução alienígena.

A proposta surgiu da necessidade de substituir um processo de controle descentralizado, sujeito a conflitos de agendamento, utilização indevida de naves, inconsistências na identificação de participantes e dificuldades de rastreabilidade das missões.

O sistema pretende oferecer suporte à gestão das missões, permitindo o controle de solicitações, a composição das equipes, a verificação das condições para autorização, o gerenciamento de ocorrências e a preservação do histórico operacional.

### 🎯 Objetivos do sistema

- Centralizar as informações relacionadas às missões.
- Organizar as solicitações e o processo de autorização.
- Controlar a composição das equipes e suas funções.
- Considerar as restrições operacionais das naves.
- Registrar ocorrências, cancelamentos e reagendamentos.
- Preservar o histórico das missões e das alterações realizadas.
- Melhorar a rastreabilidade e a organização das operações.

### 🚧 Situação atual do projeto

O projeto encontra-se na fase de **Discovery e levantamento de requisitos**. As User Stories documentadas representam o entendimento atual do negócio e servirão como base para a construção e priorização do Product Backlog.

As tecnologias e o escopo técnico apresentados neste documento são propostas iniciais para planejamento acadêmico, não decisões definitivas de arquitetura.

---

## 🛠️ 2. Tecnologias Sugeridas

As tecnologias abaixo são sugestões para avaliação durante as próximas etapas do projeto. A escolha definitiva dependerá dos requisitos consolidados, das necessidades acadêmicas e das decisões da equipe.

| Tecnologia | Finalidade sugerida |
|---|---|
| Node.js | Possível ambiente de execução do backend |
| JavaScript | Linguagem de programação sugerida para o desenvolvimento |
| HTML5 | Estrutura das páginas da aplicação web |
| CSS3 | Estilização e apresentação da interface |
| Git | Controle de versão do código-fonte |
| GitHub | Hospedagem do repositório e colaboração da equipe |
| Banco de dados | Persistência de usuários, missões, equipes e históricos |
| Markdown | Documentação do projeto |

### Observações

- A tecnologia de banco de dados ainda não foi definida.
- A arquitetura da aplicação ainda não foi estabelecida.
- A escolha entre aplicação web, aplicação móvel ou outra forma de acesso deverá ser confirmada.
- Nenhuma das tecnologias sugeridas deve ser considerada uma decisão técnica aprovada neste estágio.

---

## 🌿 3. Estratégia de Branches do Git

O repositório utilizará duas branches principais para organizar o desenvolvimento e preservar uma versão estável do projeto.

### `main` — Produção estável

A branch `main` representa a versão considerada estável do projeto.

**Diretrizes:**
- Deve conter versões revisadas e consideradas estáveis.
- Recebe alterações após validação e integração.
- Deve preservar o histórico das versões consolidadas.
- Não deve ser utilizada como branch principal para desenvolvimento diário.

### `develop` — Integração do desenvolvimento

A branch `develop` será utilizada para integrar as funcionalidades em desenvolvimento antes de sua consolidação na `main`.

**Diretrizes:**
- Centraliza a integração das funcionalidades da equipe.
- Recebe alterações provenientes das branches de trabalho.
- Deve passar por revisão e validação antes da promoção para `main`.
- Serve como base para organizar o desenvolvimento das Sprints.

### Fluxo de trabalho proposto

```text
main
  ↑
  | versão validada
  |
develop
  ↑
  | integração das funcionalidades
  |
branches de trabalho
  ├── feature/US-006-solicitacao-missao
  └── feature/US-003-composicao-equipe

  ---
```

## 🎨 4. Prototipação do Sistema

A etapa de prototipação do **ABUZ.AI GSA** tem como objetivo transformar os requisitos levantados durante o Discovery em uma representação visual e interativa do sistema.

O protótipo permitirá visualizar como os usuários irão interagir com as funcionalidades, compreender a organização das telas e avaliar os principais fluxos operacionais antes do início do desenvolvimento técnico.

A prototipação será realizada com apoio de Inteligência Artificial, utilizando prompts elaborados a partir das informações documentadas no levantamento de requisitos e nas User Stories.

### 🎯 Objetivos da prototipação

- Representar visualmente as principais funcionalidades do sistema.
- Demonstrar a navegação entre os módulos.
- Validar a organização das informações.
- Facilitar a compreensão dos fluxos de negócio.
- Identificar possíveis melhorias na experiência do usuário (UX).
- Apoiar a validação das User Stories.
- Servir como referência visual para as futuras etapas de desenvolvimento.

### 🎨 Identidade visual proposta

O protótipo seguirá uma identidade visual futurista, alinhada à temática do projeto, mantendo características de um sistema administrativo profissional.

Características definidas para a interface:

- Tema escuro (*Dark Mode*).
- Predominância de azul-marinho e preto.
- Elementos em azul, ciano e branco.
- Menu lateral para navegação entre módulos.
- Cards para indicadores e informações relevantes.
- Tabelas para listagem e gerenciamento de registros.
- Formulários para cadastro e edição.
- Indicadores visuais para representar os estados das missões.
- Layout responsivo.

### 🖥️ Módulos contemplados no protótipo

O protótipo deverá apresentar os seguintes módulos:

| Módulo | Descrição |
|---|---|
| Dashboard | Apresentação de indicadores gerais, missões recentes, solicitações pendentes e disponibilidade das naves. |
| Gestão de Missões | Consulta, cadastro e acompanhamento das missões. |
| Solicitações de Missão | Registro e acompanhamento das solicitações realizadas pelos usuários autorizados. |
| Gestão de Equipes | Visualização e gerenciamento das equipes e suas funções. |
| Gestão de Naves | Cadastro, consulta e visualização do porte, status e disponibilidade das naves. |
| Autorizações | Visualização das solicitações e respectivas decisões de autorização. |
| Solicitações de Cancelamento | Registro e acompanhamento das solicitações de cancelamento. |
| Histórico | Consulta das missões anteriores, ocorrências, cancelamentos e alterações realizadas. |
| Configurações | Área de apresentação das configurações gerais do sistema. |

### 🔗 4.1. Relação entre a prototipação e as Issues do GitHub

O protótipo interativo do ABUZ.AI GSA está disponível no link abaixo:

👉 **[Acessar Protótipo do ABUZ.AI GSA](https://stitch.google.com/projects/6289292648172246911)**

Através do protótipo, é possível visualizar a identidade visual do sistema, navegar entre os módulos e conhecer a representação das principais funcionalidades planejadas.

**Ferramenta utilizada:** [Nome da ferramenta de prototipação]

**Status:** Em desenvolvimento / Disponível para avaliação.

A prototipação contempla funcionalidades relacionadas às User Stories identificadas durante o Discovery.

A tabela abaixo apresenta a relação preliminar entre os módulos do protótipo e as histórias correspondentes.

| Módulo do protótipo | User Stories relacionadas |
|---|---|
| Dashboard | Visão geral das funcionalidades do sistema |
| Gestão de Missões | US-006, US-009 e US-015 |
| Solicitações de Missão | US-006 |
| Gestão de Equipes | US-003, US-004 e US-008 |
| Gestão de Naves | US-002 |
| Autorizações | US-007 e US-008 |
| Solicitações de Cancelamento | US-010, US-016, US-017, US-018, US-019 e US-020 |
| Histórico | US-011, US-012, US-013 e US-014 |
| Seleção de alvos | US-001 e US-005 |

**Observação:** essa associação representa a cobertura funcional planejada para o protótipo. A correspondência com as Issues efetivamente cadastradas no GitHub deverá ser conferida pela equipe. A presença de uma funcionalidade no protótipo não significa que sua implementação esteja concluída.

### 📋 4.2. Issues abrangidas pela prototipação

Considerando o Product Backlog atual, a prototipação possui relação com as seguintes Issues:

- **US-001 — Restrição de faixa etária:** representação dos critérios de seleção de alvos.
- **US-002 — Distância conforme o porte da nave:** apresentação das informações de porte e limitações da nave.
- **US-003 — Composição máxima da equipe:** representação dos integrantes e suas funções.
- **US-004 — Participação de estagiários:** representação dos estagiários na composição das equipes.
- **US-005 — Seleção de alvos:** representação das informações relacionadas aos alvos das missões.
- **US-006 — Solicitação de missão:** formulário e acompanhamento das solicitações.
- **US-007 — Autorização da missão:** representação das decisões de autorização.
- **US-008 — Verificação dos integrantes da equipe:** apresentação dos critérios de verificação dos participantes.
- **US-009 — Alteração de missão autorizada em situação crítica:** representação do gerenciamento de alterações críticas.
- **US-010 — Cancelamento e retorno diante de ocorrência:** representação do fluxo de retorno e cancelamento.
- **US-011 — Registro de ocorrência e cancelamento:** registro das ocorrências e justificativas.
- **US-012 — Consulta do histórico:** visualização dos registros anteriores.
- **US-013 — Alteração de dados históricos:** representação das funcionalidades de alteração.
- **US-014 — Rastreabilidade das alterações:** apresentação dos valores anteriores, novos valores e justificativas.
- **US-015 — Análise da ocorrência e retorno:** representação da análise realizada pelo comandante.
- **US-016 — Tratamento da missão após retorno:** representação do cancelamento temporário.
- **US-017 — Decisão de cancelamento definitivo:** representação da decisão do Controle da Missão e do alto escalão.
- **US-018 — Reagendamento:** representação da definição de uma nova data.
- **US-019 — Cancelamento antes do início:** representação do cancelamento prévio.
- **US-020 — Registro do cancelamento prévio:** registro do responsável, data e motivo.

### 🤖 4.3. Utilização de Inteligência Artificial na prototipação

A Inteligência Artificial será utilizada como ferramenta de apoio à criação das interfaces e à organização visual do sistema.

O processo consiste em:

1. Utilizar as informações levantadas durante o Discovery.
2. Elaborar prompts com a descrição dos módulos e funcionalidades.
3. Solicitar à ferramenta de IA a geração das interfaces.
4. Avaliar os resultados produzidos.
5. Comparar as telas com as User Stories e regras de negócio.
6. Ajustar o protótipo conforme as necessidades identificadas.
7. Apresentar o resultado para validação acadêmica.

A IA será utilizada como apoio à prototipação, enquanto as decisões sobre funcionalidades e regras de negócio permanecem sob responsabilidade da equipe do projeto.

### 🧪 4.4. Validação do protótipo

Após a geração das interfaces, o protótipo deverá passar por uma avaliação considerando:

- Coerência entre as telas e os requisitos.
- Facilidade de navegação.
- Organização das informações.
- Clareza dos formulários.
- Representação adequada dos estados das missões.
- Coerência entre os módulos.
- Atendimento às funcionalidades previstas nas Issues.

Os dados fictícios utilizados na demonstração deverão ser identificados como exemplos.

O protótipo não deverá apresentar como definitivas regras de negócio que ainda estejam pendentes de validação.

### 📌 4.5. Resultado esperado

Ao final da prototipação, espera-se obter uma representação visual navegável do ABUZ.AI GSA, permitindo demonstrar:

- A estrutura geral do sistema.
- Os principais módulos administrativos.
- A interação entre equipes e missões.
- O processo de solicitação e autorização.
- O gerenciamento das naves.
- O acompanhamento de ocorrências e cancelamentos.
- A consulta e preservação do histórico.

O protótipo servirá como referência para a validação dos requisitos e para o planejamento das próximas etapas do projeto.

### 📊 Status da prototipação

| Atividade | Status |
|---|---|
| Levantamento dos módulos | Planejado |
| Elaboração do prompt de prototipação | Realizado |
| Geração das interfaces com IA | Pendente |
| Navegação entre as telas | Pendente |
| Validação das interfaces | Pendente |
| Associação definitiva com as Issues do GitHub | Pendente |

**Importante:** a prototipação não representa o início automático da implementação do sistema. Seu objetivo é validar visualmente as funcionalidades antes do desenvolvimento técnico.

---
