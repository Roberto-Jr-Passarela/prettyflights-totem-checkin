# GitFlow - PrettyFlights Totem Check-in

## Objetivo

Este projeto simula o desenvolvimento da versão 1.0.0 do módulo de Totem de Check-in da PrettyFlights utilizando a estratégia GitFlow.

---

# Estrutura de Branches

## main

Branch principal de produção.

## develop

Branch de desenvolvimento contínuo.

## feature/\*

Branches usadas para desenvolvimento de funcionalidades.

Exemplo:

- feature/totem-checkin-ui

## release/\*

Branches usadas para preparação de versões.

Exemplo:

- release/1.0.0

## hotfix/\*

Branches utilizadas para correções emergenciais.

Exemplo:

- hotfix/fix-checkin-crash

---

# Fluxo Executado

## 1. Inicialização do Repositório

Foi criado um novo repositório Git local e conectado a um repositório público no GitHub.

---

## 2. Criação das Branches

Foram criadas as branches principais:

- main
- develop

E as temporárias:

- feature/totem-checkin-ui
- release/1.0.0
- hotfix/fix-checkin-crash

---

## 3. Desenvolvimento da Feature

Foi criada uma feature para implementação inicial da interface do totem de check-in.

Commit realizado:

- feat(totem): adiciona interface inicial do totem de check-in

---

## 4. Integração da Feature

A feature foi integrada na branch develop através de merge.

---

## 5. Release 1.0.0

Foi criada a release/1.0.0 a partir da develop e posteriormente integrada na main.

Tag criada:

- v1.0.0

---

## 6. Hotfix Emergencial

Foi criado um hotfix para corrigir uma falha crítica no totem de check-in.

Commit realizado:

- fix: corrige falha crítica no totem de check-in

Tag criada:

- v1.0.1

---

# Semantic Versioning

O projeto utiliza Semantic Versioning:

MAJOR.MINOR.PATCH

Exemplos:

- 1.0.0 → primeira versão estável
- 1.0.1 → correção emergencial

---

# Conventional Commits

Foram utilizados Conventional Commits para padronização:

- feat → nova funcionalidade
- fix → correção
- docs → documentação
- chore → tarefas auxiliares
