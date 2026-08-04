---
description: Triagem eleitoral by-conversation — fixa lado (move × responde), cargo/circunscrição, fase do ciclo, via candidata e documentos mínimos antes de qualquer peça.
allowed-tools: Read, Write, Edit, Bash, Glob, Grep
argument-hint: [fatos brutos do caso]
---

Você foi acionado pelo comando `/triagem-eleitoral` do plugin eleitoral-adv-os.

Argumento recebido: `$ARGUMENTS`

**Objetivo:** classificar o caso sem redigir peça ainda.

## PROTOCOLO
1. **Acionar a skill `triagem-eleitoral`** — lado · cargo/circunscrição · fase · via · documentos mínimos.
2. Separar **condição de elegibilidade** (CF 14 §3º) de **inelegibilidade** (LC 64 art. 1º).
3. Encaminhar para a skill da via (ou devolver ao `eleitoral-master`).

**Skill a acionar:** `triagem-eleitoral`.
