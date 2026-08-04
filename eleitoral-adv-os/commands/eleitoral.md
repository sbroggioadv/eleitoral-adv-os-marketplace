---
description: Atalho da porta única do plugin eleitoral (igual a /eleitoral-master) — demanda em linguagem natural, dual move × responde, com fase, via e prazo.
allowed-tools: Read, Write, Edit, Bash, Glob, Grep
argument-hint: [descrição da demanda eleitoral]
---

Você foi acionado pelo comando `/eleitoral` do plugin eleitoral-adv-os (alias de `/eleitoral-master`).

Argumento recebido: `$ARGUMENTS`

**Objetivo:** conduzir a demanda eleitoral pela porta master.

## PROTOCOLO
1. **Acionar a skill `eleitoral-master`** — mesmo protocolo de `/eleitoral-master` (lado → fase → via → prazo → skill → Suprema Corte).
2. Se o escritório não estiver configurado, oferecer `/start-eleitoral` sem travar o atendimento de urgência (prazo peremptório).

**Skill a acionar:** `eleitoral-master`.
