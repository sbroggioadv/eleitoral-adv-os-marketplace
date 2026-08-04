---
description: Inicia o wizard de configuração do plugin eleitoral — cria a pasta eleitoral/ com identidade do escritório, UF/TRE, trilha preferencial (contencioso dual · contas · penal · partidário) e modo de fluxo. Não trava o lado do caso.
allowed-tools: Read, Write, Edit, Bash, Glob, Grep
argument-hint: [--update para reconfigurar]
---

Você foi acionado pelo comando `/start-eleitoral` do plugin eleitoral-adv-os (Direito Eleitoral dual — move × responde).

Argumento recebido: `$ARGUMENTS`

**Objetivo:** configurar o plugin ao perfil do escritório antes de qualquer trilha.

## PROTOCOLO
1. **Acionar a skill `eleitoral-onboarding`** (wizard com botões via AskUserQuestion nas escolhas de lista fechada).
2. Cria `<cwd>/eleitoral/perfil.md`: identidade do escritório, UF e circunscrição (TRE/zona), trilha preferencial (contencioso dual · contas · penal · partidário), cargos típicos e modo de fluxo.
3. Se já existir, oferecer continuar / atualizar / recriar.
4. Fechar apontando a porta única (`/eleitoral-master`) e o alerta: **ciclo 2026 = base 2019 + alteração 2026**; FEFC textual **30/08** (08/09 só 🟡).

**Skill a acionar:** `eleitoral-onboarding`.
