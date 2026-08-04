---
description: Porta única do plugin eleitoral — descreva a demanda em linguagem natural; o orquestrador identifica o lado (move × responde), a fase do ciclo, a via e o prazo, dirime as 53 skills e conduz o caso até a entrega validada.
allowed-tools: Read, Write, Edit, Bash, Glob, Grep
argument-hint: [descrição da demanda eleitoral]
---

Você foi acionado pelo comando `/eleitoral-master` do plugin eleitoral-adv-os.

Argumento recebido: `$ARGUMENTS`

**Objetivo:** conduzir qualquer demanda eleitoral de ponta a ponta — dual, sem esquecer lado, via, prazo e lei vigente 2026.

## PROTOCOLO
1. **Acionar a skill `eleitoral-master`** — lê `context/metodologia-eleitoral.md` primeiro, classifica via `triagem-eleitoral`, carrega `memoria-de-caso-eleitoral`.
2. **1ª pergunta da triagem: você move ou responde?** (se ambíguo: botões impugna · defende · ambos/parecer). Em AIJE/AIME o ônus de provar o abuso é de **quem move**.
3. Fixar fase (pré-registro · registro · campanha · pós-turno · pós-diplomação) e via (AIRC | AIJE | AIME | 41-A | 73 | resposta | RCED | contas | penal | recurso | partidário).
4. **Prazo** com `calendario-e-prazos-eleitorais` (dispositivo + dies a quo + se peremptório) antes de redigir.
5. Fundação C1 quando necessário; skill side-aware da trilha; fechar por `suprema-corte-eleitoral` + `validador-eleitoral` sob `anti-alucinacao-eleitoral`.
6. Atualizar `memoria-de-caso-eleitoral`.

**Skill a acionar:** `eleitoral-master`.
