---
description: Suprema Corte Eleitoral R1–R4 — auditoria final de fatos/fase, fundamento vigente (diploma nomeado; base+alteração 2026), prazos/dies a quo e via/consequência antes de liberar a peça.
allowed-tools: Read, Grep, Glob
argument-hint: [peça a validar]
---

Você foi acionado pelo comando `/corte-eleitoral` do plugin eleitoral-adv-os.

Argumento recebido: `$ARGUMENTS`

**Objetivo:** auditar a entrega antes de liberar (read-only — não edita a peça; aponta correções).

## PROTOCOLO
1. **Acionar a skill `suprema-corte-eleitoral`** — R1 fatos/fase · R2 fundamento vigente (art. 105 diploma-nomeado; base 2019+2026) · R3 prazos/dies a quo · R4 via/competência/consequência.
2. Cruzar com `validador-eleitoral` e o guard `anti-alucinacao-eleitoral`.
3. Veredito: **LIBERADO** ou **CORRIGIR**.

**Skill a acionar:** `suprema-corte-eleitoral`.
