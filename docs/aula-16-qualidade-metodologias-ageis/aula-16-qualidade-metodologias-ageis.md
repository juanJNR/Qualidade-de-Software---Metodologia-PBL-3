# Aula 16 — Qualidade em Metodologias Ágeis — LocalEats

**Disciplina:** Qualidade de Software — Centro Universitário Senac-RS
**Prof.:** Luciano Zanuz
**Sistema em análise:** [LocalEats](https://local-eats-unisenac.vercel.app/)

## 1. Análise de Práticas Ágeis no Processo

| Prática | Existe no processo? | Como é aplicada atualmente? | Pode ser melhorada? |
|---|---|---|---|
| Planejamento iterativo | Parcial | O grupo divide o trabalho a cada nova aula/PBL, mas sem ciclos formais de planejamento | Sim, adotando sprints curtas com metas claras por semana |
| Priorização de funcionalidades | Parcial | As tarefas são feitas na ordem em que aparecem no enunciado do PBL | Sim, priorizando por risco/impacto no sistema, não só pela ordem de entrega |
| Entregas incrementais | Sim | Cada PBL gera um incremento de documentação/código entregue separadamente | Pode ser melhorada com entregas menores e mais frequentes dentro de cada PBL |
| Feedback frequente | Parcial | O feedback principal vem apenas na correção do professor | Criar momentos de feedback entre os próprios integrantes antes da entrega final |
| Trabalho colaborativo | Sim | Divisão de funcionalidades entre integrantes com apoio mútuo | Reforçar pair programming em partes mais críticas do sistema |
| Controle visual das atividades | Não | Não há quadro visual, apenas combinação verbal de tarefas | Adotar um quadro Kanban no GitHub Projects |
| Melhoria contínua | Não | Não existem retrospectivas formais ao final de cada entrega | Criar uma retrospectiva curta após cada PBL entregue |

**Conclusão (síntese):**
O grupo já demonstra pontos fortes ágeis, como entregas incrementais e
trabalho colaborativo na divisão de tarefas. As principais oportunidades de
melhoria estão na visibilidade do trabalho (falta de quadro visual) e na
ausência de momentos formais de retrospectiva, que impedem a equipe de
identificar problemas de processo antes que eles se repitam em entregas
futuras. Adotar um quadro Kanban simples e uma retrospectiva rápida ao final
de cada PBL já elevaria significativamente a maturidade ágil do processo.

---

## 2. Propostas de Melhoria Ágil

| Melhoria Proposta | Metodologia Relacionada | Benefício Esperado |
|---|---|---|
| Adotar um quadro Kanban no GitHub Projects para acompanhar tarefas de cada PBL | Kanban | Maior visibilidade do andamento e do que está pendente |
| Realizar uma retrospectiva curta (10 min) ao final de cada entrega | Scrum | Identificação contínua de problemas de processo e ajustes rápidos |
| Definir critérios mínimos de aceite antes de iniciar uma tarefa (DoR) | XP / Scrum | Reduz retrabalho por entendimento incompleto do requisito |
| Priorizar tarefas por impacto/risco em vez de ordem de leitura do enunciado | Lean Software Development | Foco do esforço da equipe nas partes mais críticas do sistema primeiro |

---

## 3. Definition of Ready (DoR)

Uma funcionalidade só entra em desenvolvimento quando:

- O requisito possui uma descrição clara do comportamento esperado.
- Os critérios de aceitação da funcionalidade estão definidos.
- Está claro qual integrante é responsável pela tarefa.
- As dependências de outras tarefas (se houver) já foram concluídas.
- O prazo de entrega da tarefa está definido e é conhecido pelo grupo.

---

## 4. Definition of Done (DoD)

Uma funcionalidade é considerada concluída quando:

- Os critérios de aceitação definidos foram atendidos.
- O código foi testado (manual ou automaticamente) e não apresenta falhas conhecidas.
- O código passou por revisão de pelo menos um outro integrante do grupo.
- A funcionalidade foi integrada ao repositório principal (merge realizado).
- A documentação relacionada (README ou arquivo do PBL) foi atualizada.
