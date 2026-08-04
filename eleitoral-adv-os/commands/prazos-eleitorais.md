---
description: Calendário e prazos eleitorais 2026 — Res. 23.760 + tabela por via com dies a quo (AIRC, AIME, 41-A, RCED, 24h, 3 dias); FEFC 30/08 ✅ e 08/09 🟡.
allowed-tools: Read, Write, Edit, Bash, Glob, Grep
argument-hint: [via ou marco do calendário]
---

Você foi acionado pelo comando `/prazos-eleitorais` do plugin eleitoral-adv-os.

Argumento recebido: `$ARGUMENTS`

**Objetivo:** fixar prazo com dispositivo + dies a quo + natureza (peremptório/contínuo).

## PROTOCOLO
1. **Acionar a skill `calendario-e-prazos-eleitorais`** (trava c).
2. Sem dies a quo = não sela. Declarar GAPs (prazo final da AIJE genérica; dies a quo 279/282).
3. Fechar por `validador-eleitoral` se a resposta for para peça.

**Skill a acionar:** `calendario-e-prazos-eleitorais`.
