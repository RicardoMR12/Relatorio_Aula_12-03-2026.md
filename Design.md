# Design do Sistema

## Visão Geral
A Plataforma Acadêmica Inteligente foi projetada com base nos princípios do pensamento computacional, visando escalabilidade e modularidade.

---

## Arquitetura

O sistema segue uma arquitetura em camadas:

- Apresentação (Frontend)
- Aplicação (Regras de negócio)
- Dados (Persistência)

---

## Módulos

### 1. Autenticação
Responsável por login, cadastro e controle de acesso.

### 2. Gestão Acadêmica
Gerencia disciplinas, matrículas e notas.

### 3. Relatórios
Geração de dashboards e indicadores.

### 4. Recomendação Inteligente
Sistema baseado em análise de desempenho.

---

## Modelo Conceitual

### Atores:
- Aluno
- Professor
- Coordenador

### Entidades principais:
- Usuário
- Disciplina
- Matrícula
- Nota

---

## Fluxos Principais

### Login:
Usuário → Autenticação → Acesso ao sistema

### Lançamento de Nota:
Professor → Seleciona disciplina → Insere nota → Sistema calcula média

### Recomendação:
Sistema analisa histórico → Identifica padrões → Gera sugestão

---

## Regras de Negócio

- Média mínima para aprovação: 6.0
- Apenas professores podem lançar notas
- Coordenadores acessam relatórios completos