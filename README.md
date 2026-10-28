# SGA

# 👽 ABUZ.AI GSA — Sistema de Gestão de Abduções

> **Projeto acadêmico de Tecnologia da Informação — Planejamento Ágil com apoio de Inteligência Artificial**

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
