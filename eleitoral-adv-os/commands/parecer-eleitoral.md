---
description: Parecer eleitoral go/no-go — diagnóstico honesto de via, prazo, ônus e chance, declarando gaps e rachas em vez de vender certeza.
allowed-tools: Read, Write, Edit, Bash, Glob, Grep
argument-hint: [pergunta do cliente + documentos]
---

Você foi acionado pelo comando `/parecer-eleitoral` do plugin eleitoral-adv-os.

Argumento recebido: `$ARGUMENTS`

**Objetivo:** emitir parecer dual com go/no-go fundamentado.

## PROTOCOLO
1. **Acionar a skill `parecer-eleitoral`**.
2. Cruzar vias com `quadro-consequencias-por-via` e prazos com `calendario-e-prazos-eleitorais`.
3. Fechar com ressalvas de gap e selos ✅/🟡.

**Skill a acionar:** `parecer-eleitoral`.
