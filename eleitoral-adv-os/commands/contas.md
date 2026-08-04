---
description: Prestação de contas dual — campanha, anuais, arrecadação/fontes vedadas e defesa de contas desaprovadas; não confundir desaprovação com cassação de diploma (via 30-A).
allowed-tools: Read, Write, Edit, Bash, Glob, Grep
argument-hint: [lado + tipo de contas + fase]
---

Você foi acionado pelo comando `/contas` do plugin eleitoral-adv-os.

Argumento recebido: `$ARGUMENTS`

**Objetivo:** auditar, prestar ou defender contas no eixo certo.

## PROTOCOLO
1. Classificar o eixo: campanha (`contas-de-campanha`) · anuais (`contas-partidarias-anuais`) · arrecadação/fontes (`arrecadacao-gastos-fontes-vedadas`) · desaprovação/defesa (`defesa-contas-desaprovadas`).
2. **Acionar a skill do eixo** (default de defesa de julgamento: `defesa-contas-desaprovadas`).
3. **Trava:** desaprovação ≠ cassação de diploma; cassação por gasto/arrecadação ilícitos exige via **30-A** (ou abuso).
4. Fechar por Suprema Corte + validador.

**Skill a acionar:** `defesa-contas-desaprovadas` (ou `contas-de-campanha` / `contas-partidarias-anuais` / `arrecadacao-gastos-fontes-vedadas`, conforme o eixo).
