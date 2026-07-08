# Aula 15 — Modelos de Maturidade — LocalEats

**Disciplina:** Qualidade de Software — Centro Universitário Senac-RS
**Prof.:** Luciano Zanuz
**Sistema em análise:** [LocalEats](https://local-eats-unisenac.vercel.app/)

## 1. Diagnóstico de Maturidade

| Critério | Sim | Parcial | Não |
|---|:---:|:---:|:---:|
| Os requisitos são documentados? | | X | |
| Existe controle de mudanças? | | X | |
| Há atividades de teste definidas? | X | | |
| Os defeitos são registrados? | | X | |
| O processo de desenvolvimento é conhecido por toda a equipe? | X | | |
| As tarefas são planejadas e acompanhadas regularmente? | | X | |
| Existe padronização para implementação de funcionalidades? | | | X |
| Os testes são executados antes da entrega das funcionalidades? | X | | |
| Há revisão de código ou validação por outro integrante da equipe? | X | | |
| A equipe utiliza ferramentas para gerenciamento das atividades? | | X | |
| Os artefatos do projeto (requisitos, testes, código) são organizados e versionados? | | X | |
| Existe rastreabilidade entre requisitos e funcionalidades implementadas? | | | X |
| A equipe realiza reuniões ou momentos de retrospectiva para identificar melhorias? | | X | |
| Existem indicadores ou métricas para acompanhar a qualidade do projeto? | | | X |

**Classificação do processo: Gerenciado**

A equipe já possui práticas básicas consolidadas — testes antes da entrega,
revisão de código e conhecimento compartilhado do fluxo de trabalho — o que
mostra que o processo não é mais totalmente informal (nível Inicial).
Porém, itens como padronização de implementação, rastreabilidade entre
requisitos e funcionalidades, e métricas de qualidade ainda não existem ou
são parciais. Isso indica que o processo é repetível na prática, mas ainda
depende fortemente do esforço individual dos integrantes, e não de padrões
e indicadores formalmente definidos, características do nível Definido ou
superior.

---

## 2. Identificação de Lacunas

| Lacuna | Impacto |
|---|---|
| Ausência de padronização na implementação de funcionalidades | Cada integrante resolve problemas semelhantes de formas diferentes, dificultando manutenção e revisão de código |
| Falta de rastreabilidade entre requisitos e funcionalidades | Difícil saber quais partes do sistema atendem a qual requisito, dificultando testes de regressão direcionados |
| Inexistência de métricas de qualidade | A equipe não consegue acompanhar objetivamente a evolução da qualidade do LocalEats ao longo do tempo |

---

## 3. Propostas de Melhoria

| Melhoria | Benefício |
|---|---|
| Criar um guia de padrões de código e estrutura de pastas para o projeto | Reduz divergência entre implementações e facilita revisão por pares |
| Vincular cada Issue/tarefa a um requisito específico no README ou board do GitHub | Cria rastreabilidade mínima entre requisito e código implementado |
| Registrar indicadores simples (nº de testes, nº de defeitos por sprint) a cada entrega | Permite acompanhar a evolução da qualidade do processo de forma objetiva ao longo do semestre |
