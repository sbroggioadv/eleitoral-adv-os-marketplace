---
description: Recursos eleitorais dual — TRE, REspe ao TSE, RO/RE ao STF, embargos de declaração e agravos de admissibilidade (CE 279/282), com prazos peremptórios e dies a quo.
allowed-tools: Read, Write, Edit, Bash, Glob, Grep
argument-hint: [decisão + instância + lado]
---

Você foi acionado pelo comando `/recurso-eleitoral` do plugin eleitoral-adv-os.

Argumento recebido: `$ARGUMENTS`

**Objetivo:** escolher e redigir o recurso certo no prazo certo (recorrente × recorrido).

## PROTOCOLO
1. Identificar a via: `recurso-ao-tre` · `respe-ao-tse` · `ro-re-ao-stf` · `embargos-declaracao-eleitoral` · `agravos-e-admissibilidade`.
2. **Acionar a skill da via** (default de admissibilidade denegada: `agravos-e-admissibilidade`).
3. **GAP:** dies a quo dos arts. **279 e 282** do CE — não inventar termo inicial se a fonte local não o fixar; prazo de 3 dias não autoriza dies a quo de memória.
4. Súmula STF 728 = GAP (não citar sem reabrir fonte). Fechar por Suprema Corte + validador.

**Skill a acionar:** `recurso-ao-tre` (ou `respe-ao-tse` / `ro-re-ao-stf` / `embargos-declaracao-eleitoral` / `agravos-e-admissibilidade`, conforme a via).
