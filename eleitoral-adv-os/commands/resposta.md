---
description: Direito de resposta (Lei 9.504 art. 58) dual — prazos 24/48/72h (e internet), recurso em 24h; não gera inelegibilidade.
allowed-tools: Read, Write, Edit, Bash, Glob, Grep
argument-hint: [veículo + ofensa + prazo]
---

Você foi acionado pelo comando `/resposta` do plugin eleitoral-adv-os.

Argumento recebido: `$ARGUMENTS`

**Objetivo:** pedir ou contestar o direito de resposta no prazo curto.

## PROTOCOLO
1. **Acionar a skill `direito-de-resposta-58`**.
2. Conferir prazos com `calendario-e-prazos-eleitorais` (24h recursal quando aplicável).
3. Fechar por Suprema Corte + validador.

**Skill a acionar:** `direito-de-resposta-58`.
