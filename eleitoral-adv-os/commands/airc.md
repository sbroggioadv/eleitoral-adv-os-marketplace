---
description: AIRC dual — impugna ou defende o registro de candidatura (legitimidade, prazo 5 dias, rito LC 64 arts. 3–15, notícia de inelegibilidade).
allowed-tools: Read, Write, Edit, Bash, Glob, Grep
argument-hint: [lado + fatos do registro/edital]
---

Você foi acionado pelo comando `/airc` do plugin eleitoral-adv-os.

Argumento recebido: `$ARGUMENTS`

**Objetivo:** impugnar ou defender o registro com o rito e o prazo corretos.

## PROTOCOLO
1. Fixar o **lado** (move = impugnante · responde = candidato/partido).
2. **Acionar a skill `airc-impugnacao-de-registro`** — prazo 5 dias (pedido/edital), rito LC 64, Res. 23.609/2019 + alterações 23.754/2026.
3. Se o núcleo for inelegibilidade/superveniência → encadear `defesa-em-inelegibilidade` e/ou `ficha-limpa-e-inelegibilidades`.
4. Fechar por `suprema-corte-eleitoral` + `validador-eleitoral`.

**Skill a acionar:** `airc-impugnacao-de-registro`.
